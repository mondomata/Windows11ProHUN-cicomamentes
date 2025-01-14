# Windows11ProHUN-cicomamentes
A legfrissebb Windows 11 Pro magyar nyelvű telepítő - cicoma mentesen.
Minden felesleges program kimarad a telepítésből.
Kimarad a telepítésből a  kötelező Microsoft fiók belépés, és kimarad a TPM biztonsági eszköz vizsgálat is.
Feladat:
1. Kell egy legalább 8 GB-os USB tároló (minden le lesz törölve a "pendrájvról", tehát ha van rajta fontos adat, mentsd el máshová).
2. Töltsd le a https://go.microsoft.com/fwlink/?linkid=2156295 helyről a Windows Media Cration Tool-t (Windows telepítő készítő eszközt.)
3. Helyezd a gépbe az USB tárolót, kattints a letöltött fájlra, és haladj végig a beállításokon (az USB tárolód válaszd ki telepítési eszközként). A végeredmény: a program letölti a Windows képfájlt, amiből létrehozható maga a Windows rendszer a gépeden.
4. Ha elkészült (ez néhány pertől fél óráig terjedhet az internet sebességtől függően), a Fájlkezelőben kattints az USB tárolód ikonjára (általában D:, vagy E: meghajtóként látható és ESD lesz a nevében.
5. Ezután másold az innen letöltött xml fájlt az USB tárhely felső könyvtárába (ahol a setup.exe is van).
6. Az USB tárolót csatlakoztasd arra gépre, amelyikre telepíteni szeretnéd a Windowst.
7. Indítsd el (vagy ha be van kapcsolva, indítsd újra) a gépet, ha megjelenik a gép logója (pl. HP, Lenovo, Asus, stb), nyomogasd folyamat a BOOT menü indító billenytűt. Pl. Esc, F10, F9, stb., ha nem tudod, keress rá a neten.
8. A boot menüben válaszd ki az USB-t, majd hagyd jóvá (Enter).
9. Ha mindent jól csináltál, a szokásos Windows telepítés hamarosan elindul az USB-ről.
