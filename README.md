# Windows11ProHUN-cicomamentes
Windows 11 Pro magyar nyelvű telepítő - cicoma mentesen. (Csak eredeti MS Windows 11 Pro telepítőkészletet - ISO-t - használj! Pl. innen: https://www.microsoft.com/hu-hu/software-download/windows11 | Keresd a "Windows 11-lemezkép (ISO) letöltése x64-es eszközökre" részt.)

<code><b>Minden felesleges program (bloatware/haszontalan, reklám, stb) kimarad a telepítésből.
Nem kötelező az online Microsoft fiókos belépés, nincs secure boot, nincs TPM2.0 biztonsági eszköz vizsgálat, így régebbi gépre is települ akár a legújabb Windows 11 Pro is.
(Ajánlott min.8GB RAM, és min. 60 GB szabad tárhely.)</b></code>

Feladatod:
1. Kell egy legalább 8 GB-os USB tároló (minden le lesz törölve a "pendrájvról", tehát ha van rajta fontos adat, mentsd el máshová; később persze újra használhatod másra).
2. Töltsd le a https://go.microsoft.com/fwlink/?linkid=2156295 helyről a Windows Media Cration Tool-t (Windows telepítő készítő eszközt.)
3. Helyezd a gépbe az USB tárolót,  és a Media Creation Toolban haladj végig a beállításokon (az USB tárolód válaszd ki telepítési eszközként). A végeredmény: a program letölti az USB tárra a Windows ISO képfájlt, amiből létrehozható maga a Windows rendszer a gépeden. (Az ISO kb 6GB lesz, de csak a töredékét használjuk!)
4. Ha elkészült (ez néhány perctől fél óráig terjedhet az internet és az USB tár sebességtől függően), a Fájlkezelőben kattints az USB tárolód ikonjára (általában D:, vagy E: meghajtóként látható és ESD lesz a nevében.
5. Ezután <b>másold az innen letöltött <code>autounattend.xml</code> fájlt az USB tárhely felső könyvtárába</b> (ahol a setup.exe is van).
6. Az USB tárolót csatlakoztasd arra gépre, amelyikre telepíteni szeretnéd a Windowst.
7. Indítsd újra a gépet, ha megjelenik a gépgyártó logója (pl. MSI, HP, Lenovo, Asus, stb), nyomd meg a <tt>BOOT menü indító billenytű</tt>t. Pl. <kbd>Esc</kbd>, <kbd>F10</kbd>, <kbd>F9</kbd>, stb., ha nem tudod, keress rá a neten, gyártónként eltérő lehet.
8. A boot menüben válaszd ki az USB-t, majd hagyd jóvá (<kbd>Enter</kbd>).
9. Ha mindent jól csináltál, a szokásos Windows telepítés hamarosan elindul az USB-ről. (Ami nem automatikus, hanem a Te választásod szerinti lesz telepítés közben: lemez/partíció választás az új Windowsnak, Wifi beállítás, helyi rendszergazda fiók felhasználó név és jelszó választás. Ami automatikus: gép és processzor megfelelési vizsgálat kihagyása, magyar nyelvi beállítások, Windows legjobb teljesítmény beállítás, Chrome böngésző és UnigetUi program telepítő installálás)
<hr>
   <tt>Mi ebben a jó?!</tt>
    <tt>A telepítés konfiguráló xml fájl automatikusan törli az összes felesleges és reklámozó/nyomkövető gyári Windows progit, cserébe telepíti automatikusan az UnigetUI programot, amelyet a Windows rendszer telepítése után nyomban elindíthatsz, ezzel bármilyen kedvenc programodat gyorsan, biztonságosan telepítheded.</tt>

2. módszer (haladóknak):
   Powershell parancsorban indítsd el ezt: <code>irm "https://github.com/memstechtips/WIMUtil/raw/main/src/WIMUtil.ps1" | iex</code>
   Haladj végig a parancsokon (angol), a megfelelő helyen illeszd be az innen letöltött <tt>autounattend.xml</tt> fájlt, majd a programmal létrehozott ISO fájlt csatlakoztatva a rendszerre, futtasd a legfelső könyvtárban lévő setup.exe-t, vagy az ISO fájlt írd ki Windows installernek legalább 8 GB-os USB tárolóra (Balena Eatcher-rel!) vagy DVD-re. 
    <hr>
🖍️Bónusz. Ha tényleg arra vágysz, hogy jól hangolt, reklám mentes és felesleges, nyomkövető programok nélküli Windowsod legyen, keresd itt a githubon a zseniális <b>TidyOS</b> programcsomagot, amivel meglévő Windows rendszered is gyönyörűen rendbe rakhatod.<sup>https://github.com/builtbybel/TidyOS/releases</sup> 👌👌👌
