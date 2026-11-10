# Plan 28

Statyczna strona z 28-tygodniowym planem treningowym (4 bloki), ramami kalorii i miejscem na pomiary oraz wyniki.

Pomiary i wyniki zapisują się tylko w przeglądarce (localStorage), nie w repozytorium.
Hasło nie jest przechowywane w postaci jawnej.

Publikacja: GitHub Pages z katalogu głównego (index.html).

## Funkcje

- Kopia zapasowa JSON (eksport/import z podglądem i cofnięciem).
- Import CSV z Hevy (parser w czystym JS, podgląd, deduplikacja, cofnięcie). Pliki testowe w `tests/fixtures/` są syntetyczne.
- Trening seria po serii z licznikiem przerwy.
- Baza ćwiczeń z wyszukiwarką i filtrami.
- Plan 28 tygodni: 7 poziomów objętości rosnących o najwyżej 3 serie na partię (bloki A–D), cele objętości na partię i tydzień, stosunek ciągnięcia do pchania w dniach górnych co najmniej 1,5 : 1, superserie ramion, mobilizacja i postawa w dniach górnych, tydzień kontrolny (6) i lżejsze tygodnie (12, 18, 24, 28). Czas wizyty nie jest limitem, aplikacja podaje tylko szacunek.
- Podwójna progresja: podpowiedź ciężaru z ostatniej sesji w aplikacji; kilogramy w planie to orientacyjne założenia.
- Fazy żywieniowe i progi decyzyjne jako zasady względne; własną masę i utrzymanie wpisujesz lokalnie (nie trafiają do repozytorium).

## Źródła danych

Baza ćwiczeń: [Free Exercise DB](https://github.com/yuhonas/free-exercise-db) (yuhonas), licencja Unlicense (domena publiczna).
`data/exercises.json` to odchudzona kopia; zdjęcia ćwiczeń z planu są w `img/ex/` (przekompresowane, bez EXIF), pozostałe ładowane leniwie z jsDelivr.
Polskie nazwy: ćwiczenia z planu i ok. 150 popularnych; reszta po angielsku z oznaczeniem „EN”.
