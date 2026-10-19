# prolog-zakupy - [PL]
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

# prolog-zakupy - [EN]
Smart Grocery Assistant & Recipe Recommendation Engine built with Prolog (SWI-Prolog).

## 📋 Project Description
This project implements an interactive smart shopping cart system in Prolog. It enables users to select products from various categories (vegetables, fruits, dairy, meat, bakery, beverages, snacks, grain products), calculates the total cost, and dynamically recommends meal recipes along with missing ingredients based on the current contents of the cart.

## 🚀 How to Run

You can run the project in two ways:

### 1. In Browser (SWISH)
1. Go to [SWISH SWI-Prolog](https://swish.swi-prolog.org/).
2. Paste the contents of `smart-cart.pl`.
3. Click **Compile** / **Consult**.
4. Run the starting query in the console:
   ```prolog
   ?- start.

2. Locally (SWI-Prolog)
1. Download and install SWI-Prolog.
2. Download smart-cart.pl from this repository.
3. Open the file in SWI-Prolog.
4. Run the starting command (remember to include the ending dot in the native console!):

   ```prolog
   ?- start.
