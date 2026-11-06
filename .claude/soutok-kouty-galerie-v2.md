Předělej galerii „Prostory, které vás čekají" na webu soutok-kouty.cz. Teď je přeplácaná: moc fotek najednou, záložky a podzáložky. Chci ji udělat jednoduše, podle vzoru vila-republika.cz/fotogalerie.

## Jak to má vypadat
- **Žádné záložky ani filtry.** Odstraň tlačítka Vše / Dům / Apartmány / Wellness / Bistro i podzáložky Přízemí / 1. patro / Podkroví.
- Sekce jsou pod sebou. Každá má **nadpis** (stejný font jako ostatní nadpisy na webu) a pod ním **jednu řadu 4 fotek** stejné velikosti a poměru stran (cca 3:2), s malou mezerou mezi nimi.
- U každé sekce vyber **4 nejlepší a nejrozmanitější fotky**, např. ložnice, obytná část s kuchyní, koupelna, terasa nebo loft. Žádné dvě skoro stejné fotky vedle sebe.
- Ostatní fotky sekce se v gridu neukazují, ale jsou v **lightboxu**. Po kliknutí na fotku se otevře lightbox s celou sekcí a listuje se jen v ní. Na čtvrté fotce může být decentní štítek „+N fotek", pokud jich má sekce víc.
- Žádná masonry mřížka s různými výškami. Všechny dlaždice mají stejný rozměr.

## Sekce (v tomto pořadí)
Apartmány rozděl podle typu dispozice z ceníku, ne podle podlaží:

1. **1+kk s předzahrádkou**: vizualizace 131/2 (jednotky 131/1–131/3)
2. **1+kk s terasou**: vizualizace 131/7 (jednotky 131/7, 131/8, 131/9, 131/12, 131/15, 131/16)
3. **1+kk s loftem**: vizualizace 131/18 a 131/21 dohromady, vyber 4 nejlepší z obou (jednotky 131/17–131/25)
4. **1+kk – vzorový apartmán**: skutečné fotky z `images/uploads/vzorovy` (jednotky 131/4, 131/10, 131/11, 131/13, 131/14). Tenhle apartmán je hotový a nafocený, nejde o vizualizaci.

## Vzorový apartmán: zdůraznit, že jde o skutečné foto
- Sekci 1+kk dej v galerii **na první místo**, před ostatní apartmány.
- Nadpis: „1+kk – vzorový apartmán". Pod něj krátký řádek, např. „Hotový apartmán, skutečné fotografie · 131/4, 131/10, 131/11, 131/13, 131/14 · od 2 590 000 Kč".
- K nadpisu přidej výrazný štítek **SKUTEČNÉ FOTO** nebo **HOTOVO** (zlatý akcent webu).
- Sekce s vizualizacemi (předzahrádka, terasa, loft) dostanou nenápadný štítek **VIZUALIZACE**. Rozdíl musí být vidět na první pohled.
- V lightboxu zobrazuj stejné označení u každé fotky: „Skutečné foto – vzorový apartmán" nebo „Vizualizace".
- Fotky ze složky `vzorovy` mají nečitelné názvy (UUID). Přejmenuj je na čitelné, např. `vzorovy-1kk-01.webp`, a zkomprimuj je pro web (WebP, cca do 400 kB). Originály nech, kde jsou.
- Pokud se fotky vzorového apartmánu někde na webu (O projektu, Investice, detaily jednotek 1+kk) dají použít jako důkaz, že projekt je reálný, navrhni mi to, ale bez mého potvrzení to neměň.
5. **Wellness**
6. **Bistro**
7. **Dům**: exteriér

Pod nadpis sekce apartmánů dej jeden krátký řádek s čísly jednotek a cenou od, např. „131/7, 131/8, 131/9, 131/12, 131/15, 131/16 · od 3 190 000 Kč". Ceny ber z dat jednotek na webu, ne napevno, aby se aktualizovaly s ceníkem. Rezervované jednotky do „od" nepočítej.

Stávající fotky interiéru, které nejsou vizualizacemi 131/2, 7, 18 ani 21, přiřaď do sekce podle toho, co na nich je (terasa, loft, předzahrádka). Pokud to z fotky nejde poznat, zeptej se mě.

Sekci bez fotek nezobrazuj. Pokud má sekce méně než 4 fotky, zobraz kolik jich je, ale nenatahuj je přes celou šířku, ať zůstanou ve stejné mřížce.

## Responzivita
- Desktop: 4 vedle sebe.
- Tablet: 2 × 2.
- Mobil: vodorovně posuvná řada (scroll-snap). Ne 4 fotky pod sebou, aby galerie nebyla nekonečná.

## Technicky
- Zachovej tmavé pozadí a styl webu (zlaté akcenty, fonty).
- Obrázky s `loading="lazy"`, rozumná velikost (WebP/AVIF, cca do 400 kB), české `alt` texty.
- Data galerie (sekce → seznam fotek → které 4 jsou v náhledu) drž v jednom datovém souboru, ať se dají snadno měnit.
- Ceníku, tabulky jednotek ani detailních stránek jednotek se nedotýkej.

Nejdřív mi ukaž, které 4 fotky jsi vybral do každé sekce (názvy souborů). Pak změny proveď, spusť build, zkontroluj výsledek na desktopu i mobilu a nasaď až po mém potvrzení.
