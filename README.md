# Windows11ProHUN-cicomamentes
A legfrissebb Windows 11 Pro magyar nyelvű telepítő - cicoma mentesen.
Minden felesleges program (bloatware/haszontalan, reklám, stb) kimarad a telepítésből.
Nem kötelező az online Microsoft fiókos belépés, és nincs TPM2.0 biztonsági eszköz vizsgálat, így régebbi gépre is települ.(Ajánlott min.8GB RAM, és min. 50GB szabad tárhely.)
Feladat:
1. Kell egy legalább 8 GB-os USB tároló (minden le lesz törölve a "pendrájvról", tehát ha van rajta fontos adat, mentsd el máshová; később persze újra használhatod másra).
2. Töltsd le a https://go.microsoft.com/fwlink/?linkid=2156295 helyről a Windows Media Cration Tool-t (Windows telepítő eszközt.)
3. Helyezd a gépbe az USB tárolót,  és a Media Creation Toolban haladj végig a beállításokon (az USB tárolód válaszd ki telepítési eszközként). A végeredmény: a program letölti az USB tárra a Windows ISO képfájlt, amiből létrehozható maga a Windows rendszer a gépeden. (Az ISO kb 6GB lesz, de csak a töredékét használjuk!)
4. Ha elkészült (ez néhány perctől fél óráig terjedhet az internet és az USB tár sebességtől függően), a Fájlkezelőben kattints az USB tárolód ikonjára (általában D:, vagy E: meghajtóként látható és ESD lesz a nevében.
5. Ezután másold az innen letöltött xml fájlt az USB tárhely felső könyvtárába (ahol a setup.exe is van).
6. Az USB tárolót csatlakoztasd arra gépre, amelyikre telepíteni szeretnéd a Windowst.
7. Indítsd újra a gépet, ha megjelenik a gépgyártó logója (pl. MSI, HP, Lenovo, Asus, stb), nyomd meg a BOOT menü indító billenytűt. Pl. <kbd>Esc</kbd>, <kbd>F10</kbd>, <kbd>F9</kbd>, stb., ha nem tudod, keress rá a neten, gyártónként eltérő lehet.
8. A boot menüben válaszd ki az USB-t, majd hagyd jóvá (<kbd>Enter</kbd>).
9. Ha mindent jól csináltál, a szokásos Windows telepítés hamarosan elindul az USB-ről.
