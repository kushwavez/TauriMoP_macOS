# TauriWoW Mists of Pandaria 5.4.8 macOS

<b>2021.06.11</b>: WoW.mfil fájl frissítve, lezárva. Ezáltal a nem töltődés fixálva.<br>
<b>2021.06.11</b>: Updated & Locked WoW.mfil in order to fix the not downloading issue


# [HU] Használat:
Egyszerűen bele kell húzni az Alkalmazások-ba és elindítani.

Ha előjön egy ablak, hogy "A(z) „TauriWoW Mists of Pandaria.app” sérült és nem nyitható meg. Helyezze át a Kukába.", navigáljunk az apphoz, nyissunk egy Terminal ablakot és írjuk be a következőt: <code>xattr -cr "ideazapp"</code> (ignoráljuk a "permission error" hibát)
Ezután nyissuk meg ismét és kattintsunk a "Megnyitás" gombra.

Ez egy minimal klienst tartalmaz, így az első indításkor sokat fog tölteni.

Ha van egy letöltött teljes kliensünk (pl. Torrenten letöltött Windows-os verzió) a kliens mappa teljes tartalmát, kivétel a WoW.mfil fájlt, másoljuk át a macOS kliens mappájába (jobb gomb a TauriWoW Mists of Pandaria.app-ra, Csomag tartalmának megjelenítése, Contents/Resources/Tauri_files/, ha rákérdez a felülírásra, nyomjunk a Cserére).
 
 ⚠️ A fájlok másolása előtt legalább egyszer el kell indítani és engedni, hogy az alap fájlokat elkezdje tölteni, különben "Sérült fájl..." hibát fogunk kapni! Miután előjött a "World of Warcraft is performing initial setup..." ablak, rányomhatunk a Cancel gombra és elkezdhetjük a másolást.
 
 Ha találkozunk ezzel a hibával ismét nyissuk meg a Terminal-t és írjuk be:
 
 <code>xattr -cr "ide húzzuk az alkalmazást"</code> majd enter ("" nélkül)
 Aztán indítsuk el. 

# [EN] How to:
Simply drag & drop to Applications and run.

If there is a window saying that "App is damaged and can't be opened. You should move it to the Trash." navigate where the app is, open up a Terminal window and write the following: <code>xattr -cr "yourapphere"</code> (ignore the permission error), enter, then open up the Launcher again and you should see a window with "Open" now. Click Open and the game should start.

It's a minimal client so it'll download a lot on first run.

If you have a full client (for ex. a Windows client from Torrent) downloaded copy the downloaded client folder except WoW.mfil file (you should not touch that) resources to the macOS client folder (right click on TauriWoW Mists of Pandaria.app, Show Package Contents, Contents/Resources/Tauri_files/, if prompted to overwrite click on Replace All).

⚠️ Before copying please start the game once to download neccessary files, if you won't do that you'll get an error saying "Damaged and cannot be opened..." After the "World of Warcraft is performing initial setup..." window come up, you could hit Cancel, then you can start copying.

If you encounter this problem open Terminal again and write:

<code>xattr -cr "drag your app here"</code> then enter (without "")
