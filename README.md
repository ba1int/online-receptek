# Online Receptkönyv

Az Online Receptkönyv egy interaktív weboldal, amely a felhasználóknak különféle recepteket kínál reggelire, ebédre és vacsorára. A felhasználók letölthetik a recepteket PDF formátumban, és visszajelzést is küldhetnek a receptekről.

## Funkciók

- **Reggeli Receptek**: Inspiráló és tápláló reggeli receptek minden ízléshez.
- **Ebéd Receptek**: Gyors és egyszerű receptek a sietős napokra.
- **Vacsora Receptek**: Különleges ételek, amelyek tökéletesen befejezik a napot.
- **Receptkönyv PDF**: A receptek letölthetőek és nyomtathatóak egy PDF fájlban.
- **Visszajelzések**: Közvetlen kapcsolattartás a látogatókkal egy beágyazott Google űrlapon keresztül.

## Projektstruktúra

/projekt
│   index.html           - A weboldal főoldala.
│   style.css            - A weboldal stíluslapja.
│
├── /tartozekok
│       receptek.pdf     - A letölthető PDF receptkönyv.
│
├── /fenykepek
│       elcso.png        - Lecsó kép.
│       lazac.png        - Grillezett lazac kép.
│       ...              - További képek.
│
└── /html
        reggeli.html     - A reggeli receptek oldala.
        ebed.html        - Az ebéd receptek oldala.
        vacsora.html     - A vacsora receptek oldala.
        pdf.html         - A PDF megjelenítő oldala.
        visszajelzesek.html - A visszajelzéseket gyűjtő oldal.


## Használat

A weboldal helyi gépen történő megtekintéséhez egyszerűen nyissa meg az `index.html` fájlt egy webböngészőben.

## Közreműködés

Minden közreműködést szívesen fogadunk! Ha hibát talál, vagy javítani szeretne valamit, nyugodtan küldjön be egy pull requestet vagy nyisson egy issue-t.

## Licenc

Ez a projekt MIT licenc alatt áll. A licenc teljes szövegéért lásd a `LICENSE` fájlt.
