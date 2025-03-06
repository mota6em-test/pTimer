# Szafari 
## Leírás
A **Szafari** egy egyjátékos, tycoon-stílusú valós idejű park szimulátor, amelyb en egy afrikai szafarit kell irányítani. A játék során a játékos a park igazgatójaként különböző feladatokat lát el, beleértve az állatok gondozását, a turisták élményének maximalizálását és a pénzügyi egyensúly fenntartását. 

A játék célja, hogy a park hosszú távon fenntarthatóan működjön, miközben a látogatók elégedettsége és a park gazdasági stabilitása is biztosított marad. A játékosnak folyamatosan egyensúlyban kell tartania a bevételeket és a kiadásokat, kezelnie kell az infrastruktúrát és figyelnie kell az állatpopuláció megfelelő összetételére.

A szafari területén növényevők és ragadozók élnek, akiknek megfelelő élőhelyet és táplálékot kell biztosítani. A turisták azért látogatják a parkot, hogy minél több és érdekesebb állatot láthassanak. A játék dinamikusan változó kihívásokkal operál, például új állatfajok megvásárlásával, infrastruktúra bővítésével és különböző események kezelésével, mint például betegségek vagy orvvadászok megjelenése.

A **Szafari** egy komplex menedzsment játék, amely ötvözi a stratégiai gondolkodást és a kreatív parképítést, miközben a játékos szabad kezet kap a park fejlesztésében és irányításában.

---

## Elvállalt feladatok
| Feladat               | Komplexitás   |
| -------------         |:-------------:|
| Alapfeladat           | 2             |
| Orvvadászok           |0,5            |
| Vadőrök               |0,5            |
| Irányítható vadőrök   |0,5            |
| Perzisztencia         |0,5            |
| #Betegségek és orvosok|0,5            |
| Hírességek            |0,5            |
| Alfajok               |0,5            |
| **Szumma**            |**5,5**        |
 
---
## Szafari Projektleírás

### ***Terv***
* [Wireframe](#wireframe)
    * [Wireframe oldal 1 – Kezdő oldal](#wireframe-oldal-1---kezdő-oldal)
    * [Wireframe oldal 2 – Világ     kiválasztása](#wireframe-oldal-2---világ-kiválasztása)
    * [Wireframe oldal 3 – Játéktér](#wireframe-oldal-3---játéktér)
* [Felhasználói történet](#felhasználói-történet)



### ***UML diagramok***
* [Használati eset diagram](#használati-eset-diagram)
* [Osztály diagram](#osztály-diagram)




---
## Wireframe
### Wireframe oldal 1 - Kezdő oldal
![Wireframe page 1](https://szofttech.inf.elte.hu/szofttech-c-2025/group-10/the-great-reserve/-/raw/master/Page_1.png?ref_type=heads "Wireframe page 1")
### Wireframe oldal 2 - Világ kiválasztása
![Wireframe page 1](https://szofttech.inf.elte.hu/szofttech-c-2025/group-10/the-great-reserve/-/raw/master/Page_2.png?ref_type=heads "Wireframe page 2")
### Wireframe oldal 3 - Játéktér
![Wireframe page 1](https://szofttech.inf.elte.hu/szofttech-c-2025/group-10/the-great-reserve/-/raw/master/Page_3.png?ref_type=heads "Wireframe page 3")

---
 
## Felhasználói történet
## Felhasználói történet

| Eset                          | Leírás |
|-------------------------------|--------|
| **Új Játék Indítása**         | **Szereplő:** Játékos  <br> **Cél:** Új játék indítása  <br> **Előfeltétel:** A játékos a főmenüben tartózkodik.  <br> **Esemény:** A játékos megnyomja az „Új játék” gombot, majd kiválasztja a nehézségi szintet.  <br> **Eredmény:** A játéktér betöltődik és a játék elindul. |
| **Játék Betöltése**           | **Szereplő:** Játékos  <br> **Cél:** Meglévő játékállás betöltése  <br> **Előfeltétel:** A játékos a főmenüben tartózkodik.  <br> **Esemény:** A játékos megnyomja a „Játék betöltése” gombot.  <br> **Eredmény:** Megjelenik a betölthető játékállások listája.  <br> **Előfeltétel:** A betölthető játékállások listája elérhető.  <br> **Esemény:** A játékos kiválasztja a megfelelő mentést.  <br> **Eredmény:** A játéktér betöltődik az adott állással. |
| **Vásárlás a Játékban**       | **Szereplő:** Játékos  <br> **Cél:** Termék vásárlása a játékbeli shopból  <br> **Előfeltétel:** A játékos a játéktéren tartózkodik.  <br> **Esemény:** A játékos megnyitja a shopot a bal alsó gomb segítségével.  <br> **Eredmény:** A shop felülete megnyílik.  <br> **Előfeltétel:** A játékos a shop felületén tartózkodik.  <br> **Esemény:** A játékos kiválaszt egy terméket.  <br> **Eredmény:** A kiválasztott termék elhelyezésre kerül a parkban. |
| **Idő Gyorsítás és Állítása** | **Szereplő:** Játékos  <br> **Cél:** Az idő sebességének módosítása  <br> **Előfeltétel:** A játékos a játéktéren tartózkodik.  <br> **Esemény:** A játékos megnyomja az idő állító gombokat a jobb alsó sarokban.  <br> **Eredmény:** Az idő sebessége a kiválasztott értékre áll be. |
| **Állat Eladása**             | **Szereplő:** Játékos  <br> **Cél:** Egy állat értékesítése  <br> **Előfeltétel:** A játékos a játéktéren tartózkodik.  <br> **Esemény:** A játékos kiválaszt egy állatot.  <br> **Eredmény:** Megjelenik az állat adatait tartalmazó panel.  <br> **Előfeltétel:** A játékos az állat információs panelján tartózkodik.  <br> **Esemény:** A játékos megnyomja az „Eladás” gombot.  <br> **Eredmény:** Az állat eltűnik a parkból, és a megfelelő pénzösszeg jóváírásra kerül a játékos egyenlegén. |
| **Belépődíj Módosítása**      | **Szereplő:** Játékos  <br> **Cél:** A park belépődíjának módosítása  <br> **Előfeltétel:** A játékos a játéktéren tartózkodik.  <br> **Esemény:** A játékos módosítja a belépődíj összegét a felső menüsoron.  <br> **Eredmény:** A belépődíj új értéke érvénybe lép. |
| **Vadőr Irányítása**          | **Szereplő:** Játékos  <br> **Cél:** A vadőr irányítása és feladatainak ellátása  <br> **Előfeltétel:** A játékos a játéktéren tartózkodik.  <br> **Esemény:** A játékos kiválasztja a vadőrt.  <br> **Eredmény:** Megjelenik a vadőr adatlapja.  <br> **Előfeltétel:** A vadőrt lehet utasítani.  <br> **Esemény:** A játékos kiad egy lövési parancsot.  <br> **Eredmény:** A kijelölt állat vagy orvvadász elpusztul. |

---

## UML diagramok
### Használati eset diagram
![Használati eset diagram](https://szofttech.inf.elte.hu/szofttech-c-2025/group-10/the-great-reserve/-/raw/master/UseCase.png?ref_type=heads "Használati eset diagram")
---
### Osztály diagram
![Osztály diagram](https://szofttech.inf.elte.hu/szofttech-c-2025/group-10/the-great-reserve/-/raw/master/Oszt%C3%A1ly_diagram.png?ref_type=heads)
 
