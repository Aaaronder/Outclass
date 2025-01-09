1. Projekt tervezése
a) Követelmények meghatározása
•	Funkcionális igények: 
o	Felhasználók regisztrálása és bejelentkezése.
o	Zenei adatbázis kezelése (előadók, stílusok, dalok, hangszerek).
o	Keresési lehetőségek biztosítása (előadó, hangszer és stílus alapján).
o	Saját lejátszási listák létrehozása és kezelése.
o	Zene fel, illetve letöltése.
•	Nem funkcionális igények: 
o	Felhasználóbarát felület.
o	Adatbiztonság (pl. jelszavak titkosítása).
o	Gyors és hatékony adatkezelés.
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
-	Zeneajánló
-	Szűrés (előadó, hangszerek, stílus)
-	Searchbar
•	Könyvtár
-	Kedvelt zenék
-	Custom lejátszási listák (zenék hozzáadása / törlése) 
•	Zenelejátszó 
-	Mindig jelenlévő overlay egyszerű vezérlőkkel (szünet, lejátszás, következő)
•	Profil
-	Személyes adatok (felhasználónév, profilkép)
-	Zene feltöltő ↦ saját zenék
-	
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
