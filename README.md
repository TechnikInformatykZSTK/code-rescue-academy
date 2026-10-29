# CODE RESCUE Academy

Interaktywny kurs JavaScript przygotowujący do kwalifikacji **INF.03**.

**Zawartość:** 34 lekcje, 5 modułów, laboratoria, misje programistyczne, tryb „Napraw kod”, mapa kompetencji i autorski próbny egzamin praktyczny.

## Uruchomienie

Otwórz plik `index.html` w nowoczesnej przeglądarce. Nie trzeba instalować serwera ani dodatkowych bibliotek do podstawowego działania kursu.

## Publikacja na GitHub Pages

1. Utwórz publiczne repozytorium `code-rescue-academy` na koncie GitHub.
2. Prześlij pliki `index.html`, `README.md`, `.nojekyll`, `PRYWATNOSC.md` i `INSTRUKCJA_PUBLIKACJI.md` do katalogu głównego gałęzi `main`.
3. W repozytorium otwórz **Settings → Pages**.
4. W sekcji **Build and deployment** wybierz **Deploy from a branch**, następnie **main** i **/(root)**, po czym zapisz.
5. Poczekaj na publikację i sprawdź adres `https://TechnikInformatykZSTK.github.io/code-rescue-academy/` (jeżeli właścicielem repozytorium jest `TechnikInformatykZSTK`).

Adres będzie publiczny: nie jest to dostęp ograniczony do uczniów. Do publikacji nie trzeba wgrywać plików z danymi uczniów.

## Dane i postępy

Postępy są zapisywane lokalnie w pamięci przeglądarki (`localStorage`) pod dotychczasowymi kluczami. GitHub Pages nie odbiera wyników uczniów i nie udostępnia panelu nauczyciela. Dane z wersji otwieranej jako lokalny plik **nie przeniosą się automatycznie** na adres GitHub Pages. Zachowaj kopię dotychczasowego pliku; jeśli aplikacja pozwala, wyeksportuj dostępne dane.

## Ograniczenia

To aplikacja edukacyjna do samodzielnej nauki, **nie system do formalnego oceniania**. Automatyczne testy nie weryfikują wszystkich możliwych przypadków. Kod ucznia uruchamia się w osadzonych ramkach `iframe` z atrybutem `sandbox="allow-scripts"` bez `allow-same-origin`, ale nie należy traktować tego jako pełnego audytu bezpieczeństwa.

Część lekcji omawia biblioteki i frameworki, a ich kompletne uruchamianie może wymagać osobnych środowisk. Część PHP/MySQL nie jest jeszcze zaimplementowana.

## Aktualizowanie

Aby opublikować kolejną wersję, zastąp `index.html` nowym plikiem i wykonaj commit. Adres strony pozostanie taki sam. Przed zmianą wersji przetestuj kurs w przeglądarce i wykonaj kopię danych.
