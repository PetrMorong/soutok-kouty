Uprav sekci „Jak to vypadá teď" (Postup výstavby) na webu Soutok Kouty tak,
aby fungovala stejně jako galerie vizualizací „Prostory, které vás čekají":

1. Místo jedné mřížky se 15 fotkami rozděl fotky do skupin podle data focení.
   Každá skupina má:
   - nadpis s datem (např. „Říjen 2026") ve stejném stylu jako nadpisy
     v galerii vizualizací (např. „1+kk s terasou")
   - pod ním řadu 4 náhledů ve stejném layoutu jako galerie vizualizací
   - na 4. náhledu překryv „+N fotek", pokud má skupina víc než 4 fotky
   - po kliknutí se otevře stejný lightbox, jaký používá galerie vizualizací,
     se všemi fotkami dané skupiny

2. Skupiny:
   - „Říjen 2026" = fotky ze složky reko_10_26 (nová, zobraz ji nahoře)
   - „Červen 2026" = stávající fotky, které jsou teď v sekci
   Řazení: nejnovější skupina nahoře.

3. Udělej to datově, ne natvrdo v HTML: jedno pole/konfigurace se seznamem
   skupin {nadpis, složka nebo seznam souborů}, abych příště jen přidal
   novou složku (např. reko_12_26) a jeden řádek do konfigurace.
   Pokud web používá CMS, přidej to tam jako opakovatelnou položku.

4. Podnadpis sekce změň z „aktuální stav z června 2026" na
   „Rekonstrukce je v plném proudu — fotky z postupu prací přidáváme průběžně.
   Dokončení plánujeme na leden 2028."

5. Obrázky z reko_10_26 zoptimalizuj stejně jako ostatní (velikost, formát,
   lazy loading). Zachovej alt texty ve tvaru „Rekonstrukce – říjen 2026 – foto N".

6. Na mobilu se má řada 4 náhledů chovat stejně jako v galerii vizualizací.
   Na konci ověř, že lightbox funguje pro obě skupiny a že se nic nerozbilo
   v galerii vizualizací.