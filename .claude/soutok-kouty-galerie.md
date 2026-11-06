Uprav web soutok-kouty.cz: přidej nové vizualizace apartmánů a rozděl galerii na sekce.

Souběžně běží jiná úprava ceníku a tabulky jednotek (nové číslování 131/1–131/25). Tabulky jednotek, ceníku ani dat jednotek se nedotýkej. Pokud data jednotek nebo detailní stránky ještě nemají nové číslování, vizualizace zatím přidej jen do galerie a napiš mi, co zbývá napojit.

## Nové vizualizace apartmánů
Ve složce `uploads` jsou nové složky s komprimovanými vizualizacemi:
- `ap 2 komprese` → jednotka 131/2 (přízemí, byt s předzahrádkou)
- `ap 7 komprese` → jednotka 131/7 (1. patro, s terasou)
- `ap 18 komprese` → jednotka 131/18 (podkroví, ubytovací jednotka s loftem)
- `ap21 komprese` → jednotka 131/21 (podkroví, byt s loftem)

Čísla složek odpovídají novému číslování (131/x). Pokud z obsahu obrázků nebo z kódu vyplývá něco jiného, zastav se a zeptej se mě.

Co s nimi:
- Obrázky si nejdřív prohlédni. Ověř, že jsou vhodné pro web; když budou zbytečně velké (víc než cca 400 kB), převeď je do WebP nebo AVIF a nech jim rozumné rozlišení. Přidej `loading="lazy"` a smysluplné `alt` texty česky, např. „Vizualizace apartmánu 131/21 – podkroví s loftem".
- Pokud existují detailní stránky jednotek, dej vizualizace do galerie na detailu dané jednotky.
- Jednotky stejné kategorie bez vlastních vizualizací ať na detailu ukazují vizualizace podobné jednotky s popiskem „Ilustrační vizualizace podobné jednotky". Přiřazení:
  - Přízemí s předzahrádkou (131/1, 131/3) → vizualizace 131/2
  - 1. patro (131/8–131/16) → vizualizace 131/7
  - Podkroví – ubytovací jednotky (131/22, 131/25) → vizualizace 131/18
  - Podkroví – byty (131/17, 131/19, 131/20, 131/23, 131/24) → vizualizace 131/21

## Rozdělení galerie na sekce
Galerie „Prostory, které vás čekají" je teď jeden společný blok fotek. Rozděl ji na sekce:
1. **Apartmány**, uvnitř rozdělené podle kategorie:
   - Přízemí s předzahrádkou
   - 1. patro s terasou
   - Podkroví s loftem
   Sem patří nové vizualizace a stávající fotky interiéru apartmánů (ložnice, kuchyňka, koupelna).
2. **Wellness**
3. **Bistro** (stávající vizualizace kavárny/bistra)

Stávající fotky roztřiď podle obsahu. Fotku exteriéru domu nech v úvodu galerie nebo v samostatné sekci „Dům"; nezahazuj ji. Pokud k některé sekci (např. Wellness) zatím žádné fotky nejsou, sekci nezobrazuj a napiš mi to.

Ovládání: sekce jako záložky nebo filtry nad galerií (Vše / Apartmány / Wellness / Bistro), u Apartmánů s podzáložkami podle kategorie. Zachovej stávající vzhled mřížky a lightbox. Lightbox ať listuje jen v rámci vybrané sekce. Na mobilu musí záložky jít posouvat do strany.

Nejdřív mi stručně ukaž, které soubory a místa budeš měnit. Pak změny proveď, spusť build, zkontroluj výsledek na desktopu i na mobilní šířce a nasaď až po mém potvrzení.
