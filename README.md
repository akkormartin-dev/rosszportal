# RosszPortál – GitHub Pages

Ez a csomag a RosszPortál statikus HTML-demóját tartalmazza, GitHub Pages publikálásra előkészítve.

## Publikálás GitHub Pages segítségével

1. Jelentkezz be vagy regisztrálj a https://github.com oldalon.
2. Kattints a **New repository** gombra.
3. A repository neve legyen például `rosszportal`.
4. Állítsd **Public** értékre, majd hozd létre a repositoryt.
5. A repository oldalán válaszd az **Add file → Upload files** lehetőséget.
6. Töltsd fel a csomagban lévő `index.html` fájlt a repository gyökerébe (ne egy almappába).
7. Kattints a **Commit changes** gombra.
8. Nyisd meg a repositoryban a **Settings → Pages** oldalt.
9. A **Build and deployment** résznél a Source legyen **Deploy from a branch**.
10. Branch: **main**, mappa: **/(root)**, majd **Save**.
11. Várj néhány percet, majd frissítsd a Pages beállítások oldalát. Ott megjelenik a közzétett weboldal címe. A címe tipikusan:
    `https://FELHASZNALONEV.github.io/rosszportal/`

## Fontos tudnivalók

- A `FELHASZNALONEV` helyére a GitHub-felhasználóneved kerül.
- A publikálás első alkalommal pár percet igénybe vehet.
- Ez egy statikus demó: a hirdetésfeladás és az interakciók nem használnak központi adatbázist. A beküldött új hirdetések nem lesznek minden látogató számára láthatók, és oldalfrissítés után elveszhetnek.
- Saját domain nem szükséges, a GitHub Pages címe ingyenes.
