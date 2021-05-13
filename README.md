# TauriWoW Mists of Pandaria 5.4.8 macOS

<b>Frissítés 2021.05.13:</b> A Blizzard variált a szervereivel és ennek hatására a felülírt WoW.mfil fájl miatt a Minimal Kliens nem működik (nem tölt). A Launcher így is használható, első indítás után lépj ki, navigálj az "Applications/TauriWoW Mists of Pandaria.app/Contents/Resources/Tauri_files" mappába, cseréld ki a WoW.mfil fájlt az <a href=http://devil.tauri.hu/~aithne/WoW.mfil>erről a linkről</a> letöltöttre, jobb gomb rá, Get Info (vagy Info megjelenítése) Locked=PIPA (vagy Zárolt). Ezek után indítsd el a Launchert ismét, utána jó lesz. 



<b>Update 2021.05.13:</b>Blizzard made changes to their servers, causing the minimal client won't downloading the files and won't connecting because of the WoW.mfil file inside "Applications/TauriWoW Mists of Pandaria.app/Contents/Resources/Tauri_files". The issue can be workarounded by launcing the app first, closing the app, downloading <a href=http://devil.tauri.hu/~aithne/WoW.mfil>this WoW.mfil file</a> and replace the WoW.mfil file in "Applications/TauriWoW Mists of Pandaria.app/Contents/Resources/Tauri_files", Right click on the replaced WoW.mfil file, Get Info, tick "Locked", then launch the Launcher again, should work.

HU:
# Használat:
Egyszerűen bele kell húzni az Alkalmazások-ba és elindítani.
Ha előjön egy ablak, hogy "...nem nyitható meg, mert az Apple nem tudja ellenőrizni, hogy tartalmaz-e kártékony szoftvereket." nyomjunk a "Megjelenítés a Finderben"-re, Jobb gomb az .app-ra, "Megnyitás", megint "Megnyitás" és utána működik.
Ez egy minimal klienst tartalmaz, így az első indításkor sokat fog tölteni.

Ha van egy letöltött teljes kliensünk (pl. Torrenten letöltött Windows-os verzió) a kliens mappa tartalmát másoljuk át a macOS kliens mappájába (jobb gomb a TauriWoW Mists of Pandaria.app-ra, Csomag tartalmának megjelenítése, Contents/Resources/Tauri_files/, ha rákérdez a felülírásra, nyomjunk a Cserére).
 
 ⚠️ A fájlok másolása előtt legalább egyszer el kell indítani és engedni, hogy az alap fájlokat elkezdje tölteni, különben "Sérült fájl..." hibát fogunk kapni! Miután előjött a "World of Warcraft is performing initial setup..." ablak, rányomhatunk a Cancel gombra és elkezdhetjük a másolást.
 
 Ha találkozunk ezzel a hibával nyissuk meg a Terminal-t és írjuk be:
 
 "xattr -cr {ide húzzuk az alkalmazást}" majd enter ({} nélkül)
 Aztán indítsuk el. 

Letöltési link: https://github.com/vaczi001/TauriMoP_macOS/releases/

EN:
# How to:
Simply drag & drop to Applications and run.
If there is a window saying that "...can't be opened because Apple cannot check it for malicious software." Click "Show in Finder" then Right click on the .app, and click "Open", then again "Open" and you should be fine.

It's a minimal client so it'll download a lot on first run.

If you have a full client (for ex. a Windows client from Torrent) downloaded copy the downloaded client folder resources to the macOS client folder (right click on TauriWoW Mists of Pandaria.app, Show Package Contents, Contents/Resources/Tauri_files/, if prompted to overwrite click on Replace All).

⚠️ Before copying please start the game once to download neccessary files, if you won't do that you'll get an error saying "Damaged and cannot be opened..." After the "World of Warcraft is performing initial setup..." window come up, you could hit Cancel, then you can start copying.

If you encounter this problem open Terminal and write:

"xattr -cr {drag the application here}" then enter (without {})

Download Link: https://github.com/vaczi001/TauriMoP_macOS/releases/
