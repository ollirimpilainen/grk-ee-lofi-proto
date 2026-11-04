# GRK Eesti · lo-fi-prototyyppi

Klikattava prototyyppi GRK Eestin uudesta vironkielisestä sivustosta lo-fi-tasolla. Sivut ovat GRK lo-fi -kankaan Eesti-sivulta, ja ne käyttävät samoja lohkoja kuin GRK:n suomenkielinen prototyyppi. Rakenne ja lohkot ovat ehdotus Viron työpajan (28.10.2026) pohjalta. Viron tiimi tarkistaa ilmaukset, ja visuaalinen ilme tehdään myöhemmin. Kuvat ovat paikkamerkkejä; kaaviot ja ikonit näkyvät.

Staattiset HTML-sivut, ei build-vaihetta. Julkaisupeili esittelyä varten, ei näy hakukoneissa (`noindex` ja `robots.txt`).

## Sivut

| Sivu | Tiedosto | Polku sivustolla |
|---|---|---|
| Avaleht | index.html | / |
| Teenused | teenused.html | /teenused/ |
| Teedeehitus | teedeehitus.html | /teenused/teedeehitus/ |
| Sillad ja viaduktid | sillad.html | /teenused/sillad/ |
| Raudtee-ehitus | raudtee.html | /teenused/raudtee-ehitus/ |
| Raudtee elektrifitseerimine | elektrifitseerimine.html | /teenused/elektrifitseerimine/ |
| Rail Baltica (projektileht) | rail-baltica.html | /referentsid/rail-baltica/ |
| Referentsid | referentsid.html | /referentsid/ |
| Uudised | uudised.html | /uudised/ |
| GRK Eesti | grk-eesti.html | /ettevote/ |
| Karjäär (sisältää tööpakkumised, #toopakkumised) | karjaar.html | /karjaar/ |
| Kontakt | kontakt.html | /kontakt/ |
| Kontaktisikud | kontaktisikud.html | /kontakt/kontaktisikud/ |
| Kirjelda oma projekti | paring.html | /kontakt/paring/ |

Erillinen Tööpakkumised-sivu on yhdistetty Karjääriin (4.11.2026); vanha osoite toopakkumised.html ohjaa osioon karjaar.html#toopakkumised. Valikko noudattaa kankaan EE-Navigaatio-karttaa.

Linkki sivulle, jota ei vielä ole, avaa tyhjän sivun sivun nimellä. Toiminnot (haku, lataukset) näyttävät ilmoituksen. Lomakkeet eivät lähetä tietoja. Yhteyshenkilöt ovat grk.fi/ee:n oikeat henkilöt (luettu 2.11.2026).

GRK:n prototyyppi: https://ollirimpilainen.github.io/grk-lofi-proto/
GRK Sverige: https://ollirimpilainen.github.io/grk-se-lofi-proto/

## Päivitys

Sivut generoidaan kankaan tiedostoista: `GRK/multisite/tools/ee_proto.py <kankaan project> <assetit> <archivo.woff2> <navigaatio-proto/index.html> <kohde>`. SEO-otsikot ja avoimet kysymykset: `GRK/sisaltobriefi/seo-geo-ee-2026-11-02.md`.
