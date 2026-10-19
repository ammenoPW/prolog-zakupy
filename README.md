# prolog-zakupy
Inteligentny asystent zakupów i system rekomendacji dań napisany w języku Prolog (SWI-Prolog).

## Opis projektu:
Projekt realizuje funkcje inteligentnego koszyka zakupowego. Pozwala użytkownikowi wybierać produkty z różnych kategorii (warzywa, owoce, nabiał, mięso, pieczywo, napoje, przekąski, produkty zbożowe), sumuje koszt zakupów oraz na podstawie zawartości koszyka inteligentnie podpowiada przepisy i automatycznie proponuje brakujące składniki.

## Jak uruchomić projekt?

Projekt można uruchomić na dwa sposoby:

### 1. Przez przeglądarkę (SWISH)
1. Wejdź na stronę [SWISH SWI-Prolog](https://swish.swi-prolog.org/).
2. Wklej zawartość pliku `smart-cart.pl`.
3. Kliknij **Compile** / **Consult**.
4. W konsoli wpisz komendę:
   ```prolog
   ?- start.

### 2. Lokalnie na komputerze (SWI-Prolog)
1. Pobierz i zainstaluj SWI-Prolog.
2. Pobierz plik smart-cart.pl z tego repozytorium.
3. Otwórz plik w programie SWI-Prolog (lub uruchom go przez konsolę).
4. Wpisz komendę startową (pamiętaj o kropce na końcu w tradycyjnej konsoli!):
   ```prolog
   ?- start.
