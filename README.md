# BRYUM – aktuální web (střechy + renovace podlah)

Statický web pro GitHub Pages a doménu `bryumcisteni.cz`.

## Struktura nabídky
- **Čištění a impregnace střech:** kompletní postup 147 Kč/m² (biocid 29 Kč/m², čištění vapkou 64 Kč/m², impregnace 54 Kč/m²).
- **Renovace a ochrana betonových a minerálních podlah:** aplikace IG CeramFloor 499 Kč/m².
- **Příprava podlahy:** odmaštění, odstranění minerálních usazenin a případné další vrstvy se posuzují a nacení individuálně podle stavu podkladu.
- **Výškové práce:** samostatná služba s individuální nabídkou.
- BRYUM není plátcem DPH.

## Hlavní stránky
- `index.html` – přehled obou hlavních specializací, ceník, recenze a FAQ.
- `cisteni-strech.html` – detailní stránka čištění střech.
- `renovace-betonovych-podlah.html` – detailní stránka systému IG CeramFloor, vlastností, použití a ceny.
- `vyskove-prace.html` – výškové práce.
- `poptavka.html` – společný poptávkový formulář s kalkulací pro střechy i podlahy a individuální volbou výškových prací.
- `kontakty.html` – kontaktní informace a působnost.
- `dekujeme.html`, `404.html` – pomocné stránky.
- `keramicka-ochrana-podlah.html` a `cisteni-okapu.html` – staré adresy přesměrované na aktuální stránky.

## Poptávkový formulář
- Formulář odesílá JSON v UTF-8 na Web3Forms.
- Během odesílání ukazuje stav „Odesílám poptávku…“.
- Jméno není povinné; e-mail je povinný a telefon nepovinný.
- Plocha střechy zůstává trvale viditelná pod třemi střešními volbami; povinná je jen při výběru střešní služby.
- Pro IG CeramFloor je uvedena sazba 499 Kč/m² za aplikaci. Příprava podkladu a případné další vrstvy se oceňují individuálně.
- Obyčejné otevření formuláře nemá předvybranou žádnou službu. Odkaz `poptavka.html?sluzba=podlahy` předvybere podlahy; `?sluzba=strechy` předvybere čištění střech.

## Technické podklady IG CeramFloor
Texty o vlastnostech a použití vycházejí z uživatelem dodaného českého technického listu IG CeramFloor. Výrobce uvádí mimo jiné test abraze EN 13892-5 se zlepšením o 92,5 %, možnost použití na vhodných vyhřívaných površích a pochozí stav přibližně po 24 hodinách. Uváděná životnost „až 10 let“ je prezentována jako údaj výrobce, nikoli jako automatická záruka.

## Nasazení na GitHub Pages
1. Rozbalte ZIP.
2. Nahraďte soubory v kořenové složce repozitáře soubory z balíčku.
3. Zachovejte `CNAME` v kořeni repozitáře.
4. Ponechte GitHub Pages nastavené na `main` a `/(root)`.
5. Po publikaci otestujte hlavní stránku, mobilní zobrazení, formulář střechy, formulář podlah a doručení e-mailu.

## SEO a analytika
Web obsahuje aktualizované titulky, meta popisy, canonical URL, Open Graph, strukturovaná data, `robots.txt` a `sitemap.xml`. Cloudflare Web Analytics zůstává zachováno.

## Kontakty
- Telefon: +420 799 522 522
- E-mail: info@bryumcisteni.cz
- Oblast působnosti: Zlínsko a Vysočina; po dohodě celá ČR.


Aktualizace 24. 11. 2026: Stránka IG CeramFloor více cílí na garáže, autoservisy, dílny a průmyslové haly. Doplněny jsou vlastní vektorové piktogramy, schématická ilustrace ochranné vrstvy a samostatný náhledový obrázek pro sdílení. Text rozlišuje obecné oleofobní vlastnosti a nutnost ověřit konkrétní provozní emulze.


## Hlavní stránka – dvojice služeb

- Úvodní část nyní představuje čištění střech a ochranu podlah přímo ve dvou hlavních kartách.
- Na počítači jsou karty vedle sebe; na mobilu jsou pod sebou a nad nimi je rychlá volba obou služeb.
- Karta střech používá skutečné video `media/hero-drone.mp4`; karta podlah používá ilustrační vizualizaci.
- Pochoznost podlahy přibližně po 24 hodinách je zvýrazněna přímo v kartě podlah.
- Zachovány jsou ceny, formulář, SEO, analytika, původní logo, `CNAME` a ostatní stránky.
