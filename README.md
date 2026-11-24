# BRYUM Čištění – aktuální web

Statický web připravený pro GitHub Pages a doménu `bryumcisteni.cz`.

## Nahrání na GitHub Pages
1. Rozbalte ZIP.
2. Nahraďte obsah kořenové složky repozitáře soubory z tohoto balíčku.
3. Zachovejte `CNAME` v kořeni repozitáře.
4. V GitHubu ponechte **Settings → Pages → Deploy from a branch → main → /(root)**.
5. Po publikaci otestujte hlavní stránku, formulář a mobilní zobrazení.

## Služby a ceny
- **Hlavní služba: kompletní čištění střechy – 147 Kč/m².**
- Položkový rozpis kompletního balíčku:
  - Biocidní ošetření: **29 Kč/m²**
  - Čištění vapkou: **64 Kč/m²**
  - Impregnace: **54 Kč/m²**
- Tyto tři položky tvoří jeden navazující kompletní postup; nejsou nabízeny samostatně.
- **Čištění okapů je zdarma při objednání kompletního čištění střechy.** Samostatné objednávky čištění okapů se nenabízejí.
- **Výškové práce** jsou samostatnou službou s individuální cenovou nabídkou.
- BRYUM není plátcem DPH.

## Obsah webu
- `index.html` – hlavní stránka, služby, ceník, recenze a FAQ
- `cisteni-strech.html` – rozšířená stránka hlavní služby a podrobný ceník
- `cisteni-okapu.html` – informační stránka: okapy zdarma jako součást kompletního čištění střechy
- `vyskove-prace.html` – samostatná nabídka výškových prací
- `poptavka.html` – poptávkový formulář s kalkulačkou
- `kontakty.html` – kontakty a sídla
- `dekujeme.html`, `404.html` – pomocné stránky
- `site.css`, `site.js` – společný vzhled a mobilní navigace
- `images/` – logo a fotografie
- `media/hero-drone.mp4` – úvodní video z dronu
- `robots.txt`, `sitemap.xml` – základní soubory pro vyhledávače

## Poptávkový formulář a kalkulačka
Kalkulačka počítá kompletní čištění střechy jako součet tří položek:
- plocha × 29 Kč/m² za biocidní ošetření,
- plocha × 64 Kč/m² za čištění vapkou,
- plocha × 54 Kč/m² za impregnaci.

Výsledkem je **147 Kč/m²**. Kalkulace zároveň uvádí čištění okapů zdarma jako součást kompletního balíčku. Výškové práce lze vybrat samostatně a jejich cena se stanoví individuálně. Formulář odesílá poptávku přes původní FormSubmit endpoint a po úspěšném odeslání zobrazuje potvrzení přímo ve formuláři.

## SEO a analytika
Web obsahuje titulky a meta popisy, canonical URL, Open Graph, strukturovaná data, popisy obrázků, `robots.txt` a `sitemap.xml`. Cloudflare Web Analytics je vloženo do všech HTML stránek. Po publikaci doporučujeme zkontrolovat doménu v Google Search Console a Seznam Webmaster a odeslat sitemapu `https://bryumcisteni.cz/sitemap.xml`.

## Kontakty
- Telefon: +420 799 522 522
- E-mail: info@bryumcisteni.cz
- Oblast působnosti: Zlínsko a Vysočina; po dohodě celá ČR.
