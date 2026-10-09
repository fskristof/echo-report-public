# EchoCore – kézi kitöltés (nyilvános változat)

Echokardiográfiás lelet kézi kitöltéshez: a mezőkbe írt értékekből a program kiszámolja a származtatott értékeket
(BSA, E/A, AVA, ERO, Reg. vol. …), ellenőrzi őket, és a kórházi rendszerbe másolható, formázott leletszöveget készít.

**Hogyan működik:** a teljes program a böngésződben fut (Python a böngészőben, [Pyodide](https://pyodide.org)).
Amit beírsz, nem kerül el sehova: nincs szerver, nincs mentés, nincs adatgyűjtés. Ne írj be betegazonosító adatot.

**Fontos:** segédeszköz, nem orvostechnikai eszköz. A lelet tartalmáért a kitöltő orvos felel; minden számolt értéket
ellenőrizz.

Ez a mappa automatikusan készül a program privát forrásából (`build_public.py`); itt ne szerkeszd kézzel.
A Pyodide a Mozilla Public License 2.0 alatt áll (`pyodide/LICENSE`).
