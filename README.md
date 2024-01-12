○ Vizsga során használt Git parancsok:


git clone https://github.com/szabopeter92/git-vizsga -> Ezzel a paranccsal klónoztam le a vizsgafeladatot a saját gépemre.

git status - Leellenőrzi a repository-ban fájlok állapotát.

git add README.md - Hozzáadja az úgynevezett Stating Area- hoz az újonnan létrehozott/módostott README.md-t
git add . - Hozzáadja az úgynevezett Stating Area- hoz az újonnan létrehozott fájlokat.

git branch - Kilistázza a meglévő ágakat.
git branch console - Létrehozza a console nevű ágat.
git checkout console - Belép a console ágba.

git remote set-url origin https://github.com/Teglasadam/git-vizsga.git - a megadott URLre módosítja a a feltöltési útvonalat.

git push --all origin - Minden ágat feltölt a megadott könyvtárba.

git reset --soft azonostó - Ezzel kitörölgettem a felesleges README.md szükséges commitolására szolgáló verziókat.

○ Feladat kivitelezésének menete: 


Leklónoztam saját gépre a vizsgafeladatot terminálból, majd ezután elindtottam a VSCodeot és létrehoztam a README.md fájlt amit sikeresen felcommitoltam.

A .gitignore fájl létrehozása után feltöltöttem a feladatban szereplő ignorációkkal majd szintén felcommitoltam.

Ezután leelenőriztem milyen ágak vannak létrehozva. A main ágon kívül nem volt egyéb ág, így létrehoztam a "console" ágat. Ezután egy ismételten sikeres commit következett. 

Beléptem a console ágba.

Módosítottam az app.js fájlt úgy, hogy az oldal betöltődésére írja ki a consoleba a megfelelő szöveget amit felcommitoltam.

Módosítottam a style.css body részlegén belül az átmenetes háttérszínt aztán commitoltam.git remote 

Módosítottam a feltöltési URLt.

Végül feltöltöttem merge nélkül mindkét ágat a github könyvtáramba.

Kiegészítésként kitöröltem a README.md módosítása miatt létrehozott commitokat. Illetve kitöltöttem a console ág README.md t az ott megtörtént változtatásokkal.


