# WaterGate

**Prohlížeč, který si poskládáte podle sebe.** WaterGate stojí na jádře Firefoxu a přidává to,
co znáte z Vivaldi: boční panely, skupiny listů, pracovní prostory, dlaždice, rychlé příkazy,
gesta a editor lišt. K tomu aplikace pro Android, která s počítačem sdílí data a umí ho dálkově ovládat.

[![Prohlídka WaterGate (video, 3 min)](https://github.com/WaterDrag/WaterGate/releases/latest/download/tour-poster.jpg)](https://github.com/WaterDrag/WaterGate/releases/latest/download/tour.mp4)

▶ [Prohlídka funkcí – video](https://github.com/WaterDrag/WaterGate/releases/latest/download/tour.mp4)

## Stažení

| Systém | Soubor | |
| --- | --- | --- |
| Windows 10/11 | [WaterGate-Setup.exe](https://github.com/WaterDrag/WaterGate/releases/latest/download/WaterGate-Setup.exe) | instalace pro jednoho uživatele, bez práv správce |
| Windows (přenosná verze) | [WaterGate-win64-portable.zip](https://github.com/WaterDrag/WaterGate/releases/latest/download/WaterGate-win64-portable.zip) | rozbalit a spustit `WaterGate.cmd` |
| Linux | [WaterGate-linux-x86_64.tar.xz](https://github.com/WaterDrag/WaterGate/releases/latest/download/WaterGate-linux-x86_64.tar.xz) | |
| Android | [WaterGate-Mobile.apk](https://github.com/WaterDrag/WaterGate/releases/latest/download/WaterGate-Mobile.apk) | povolte instalaci z neznámých zdrojů |

WaterGate se pak aktualizuje sám. Windows může u instalátoru ukázat varování SmartScreen
(„Neznámý vydavatel“) – pokračujte přes **Další informace → Přesto spustit**.

Při prvním spuštění vás provede uvítací stránka: import záložek a hesel z jiného prohlížeče,
přihlášení k synchronizaci a nastavení výchozího prohlížeče.

## Co umí

**Na počítači**
- **Boční panel** (F4): záložky, historie (i nedávno zavřené), stahování, poznámky, seznam četby,
  překladač, pošta, kalendář, úkoly, odběry a kontakty. Ukotvený, nebo plovoucí přes stránku.
- **Webové panely**: libovolný web v bočním panelu, s odznakem nepřečtených zpráv.
- **Skupiny listů**: list přetažený na jiný list vytvoří skupinu, druhá řada ukáže její listy.
- **Pracovní prostory**: oddělené sady listů; vidíte i listy otevřené na telefonu a dalších počítačích.
- **Dlaždicování**: dva až čtyři listy vedle sebe, pod sebou nebo v mřížce.
- **Rychlé příkazy** (F2): příkazy, listy, záložky, historie, kalkulačka; řetězce příkazů a vlastní zkratky.
- **Gesta myší**, **editor lišt** (každé tlačítko na kteroukoli lištu), **motivy** a barva podle stránky,
  tmavý režim webů, plánované přepínání vzhledu.
- **Uspávání listů** a „Vždy vzhůru“ pro listy, které mají běžet.
- **Nastavení** (Ctrl+F12) s nápovědou a příkladem u každé volby.
- Předinstalovaný **uBlock Origin**, vypnutá telemetrie.

**Na telefonu (WaterGate Mobile)**
- Synchronizace záložek, historie, hesel a otevřených listů s počítačem (účet Mozilla).
- Ukládání a vyplňování hesel, panely, doplňky, blokování sledovacích prvků.
- **Ovládání počítače**: spárování QR kódem, přepínání listů, přehrávání a hlasitost,
  zrcadlení stránky do telefonu s klepáním a psaním.

## Hlášení chyb

V **Nastavení → Všeobecné → Záznam chyb a pádů** klikněte na **Kopírovat záznam** a pošlete ho
v [Issues](https://github.com/WaterDrag/WaterGate/issues) s popisem, co jste dělali. Záznam obsahuje
jen chyby WaterGate, ne navštívené stránky.

## Zdrojový kód

WaterGate je postavený na jádru prohlížeče Firefox od Mozilly a je šířený pod licencí
[Mozilla Public License 2.0](https://www.mozilla.org/MPL/2.0/). Zdrojový kód každé verze WaterGate
je přiložený u jejího vydání jako `WaterGate-source.zip`; zdrojový kód Firefoxu najdete na
[archive.mozilla.org](https://archive.mozilla.org/pub/firefox/releases/).
WaterGate není produktem Mozilly; Firefox je ochranná známka Mozilla Foundation.
