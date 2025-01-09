Outclass
1. Projekt tervezése
a) Követelmények meghatározása
A projekt első lépése a követelmények pontos és részletes meghatározása. Ebbe beletartozik mind a funkcionális, mind a nem funkcionális igények rögzítését, hogy a fejlesztés során minden elvárásnak megfelelően haladhassunk.
•	Funkcionális igények: 
o	Felhasználók regisztrálása és bejelentkezése.
	A felhasználók létrehozhatnak egyéni fiókot és bejelentkezhetnek a rendszerbe személyes hitelesítő adataik használatával.
o	Zenei adatbázis kezelése (előadók, stílusok, dalok, hangszerek).
	Az alkalmazásnak képesnek kell lennie különböző zenei adatbázis-elemek, például előadók, zenei stílusok, dalok és hangszerek tárolására és kezelésére.
o	Keresési lehetőségek biztosítása (előadó, hangszer és stílus alapján).
	A felhasználók könnyedén kereshetnek a rendszerben különböző szempontok alapján, például előadó, hangszer vagy stílus szerint.
o	Saját lejátszási listák létrehozása és kezelése.
	A regisztrált felhasználók személyre szabott lejátszási listákat hozhatnak létre, módosíthatnak és törölhetnek.
o	Zene fel, illetve letöltése.
	A felhasználók számára lehetőség nyílik zeneszámok feltöltésére a rendszerbe, illetve a meglévő fájlok letöltésére.
•	Nem funkcionális igények: 
o	Felhasználóbarát felület.
	Az alkalmazásnak intuitív és könnyen kezelhető felhasználói élményt kell nyújtania, hogy a különböző képességű felhasználók is egyszerűen tudják használni.
o	Adatbiztonság (pl. jelszavak titkosítása).
	Az érzékeny adatok, például a felhasználói jelszavak titkosított formában kerülnek tárolásra, hogy megvédjék azokat az illetéktelen hozzáféréstől.
o	Gyors és hatékony adatkezelés.
	A rendszernek nagy mennyiségű adatot kell gyorsan és megbízhatóan kezelnie, hogy a felhasználók ne tapasztaljanak teljesítményproblémákat.
b) Adatbázis tervezése
Példa adatbázis struktúrára:
•	Users: felhasználók adatai (ID, név, e-mail, jelszó).
•	Songs: dalok adatai (ID, cím, előadó, stílus, használt hangszerek).
•	Playlists: lejátszási listák (ID, név, felhasználó ID).
________________________________________
2. Fejlesztői környezet beállítása
•	Nyelv: C# (Windows Forms/WPF), webes környezet esetén JavaScript.
•	Frontend: HTML, CSS, JavaScript.
•	Adatbázis: MySQL.
•	Framework: Ha webes, ASP.NET Core; asztali alkalmazás esetén .NET Windows Forms.
•	Fejlesztői eszközök: Visual Studio, Git verziókövetés.
________________________________________
3. Felhasználói felület kialakítása
a) Regisztráció és bejelentkezés
•	Regisztrációs űrlap (név, e-mail, jelszó, profilkép).
•	Bejelentkezési felület.
b) Fő funkciók UI-ja
•	Keresés (szűrők: előadó, hangszerek, stílus).
o	Zeneajánló
o	Szűrés (előadó, hangszerek, stílus)
o	Searchbar
•	Könyvtár
o	Kedvelt zenék
o	Custom lejátszási listák (zenék hozzáadása / törlése) 
•	Zenelejátszó 
o	Mindig jelenlévő overlay egyszerű vezérlőkkel (szünet, lejátszás, következő)
•	Profil
o	Személyes adatok (felhasználónév, profilkép)
o	Zene feltöltő ↦ saját zenék
________________________________________
4. Backend fejlesztés
a) Adatbázis-kezelés
•	Kapcsolat létrehozása az adatbázissal (ADO.NET).
•	CRUD műveletek (Create, Read, Update, Delete) megvalósítása.
b) Felhasználói funkciók
•	Felhasználói regisztráció (jelszó titkosítása, pl. bcrypt).
•	Bejelentkezési folyamat (auth tokenek, session kezelés).
•	Keresési logika (előadó, stílus szerint).
•	Lejátszási listák létrehozása, módosítása, törlése.
________________________________________
5. Zenei tartalom kezelése
a) Zene adatbázis betöltése
•	Publikus API-k használata (pl. Spotify API, Deezer API), vagy saját adatbázis létrehozása.
•	MP3 fájlok kezelése (lokálisan tárolt fájlok).
________________________________________
6. Tesztelés
•	Egységtesztek: CRUD műveletek, keresési funkciók, regisztráció és bejelentkezés.
•	Integrációs tesztek: Adatbázis és UI közötti kommunikáció tesztelése.
•	Felhasználói tesztelés: Felület egyszerűsége, reszponzív felület, hibák észlelése.
________________________________________
7. Telepítés és karbantartás
•	Az alkalmazás telepítő csomagjának elkészítése (Webalkalmazás hostolása).
•	Felhasználói visszajelzések gyűjtése és hibajavítás.
________________________________________
