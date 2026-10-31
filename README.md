# Analiza wielowymiarowa atrakcyjności miast wojewódzkich w Polsce

## Opis projektu
Projekt zrealizowany w ramach studiów na kierunku Informatyka i Ekonometria (AGH). Celem pracy była ocena oraz wielowymiarowa analiza porównawcza atrakcyjności życiowej 18 miast wojewódzkich w Polsce.Na podstawie wybranych wskaźników statystycznych stworzono ranking miast oraz pogrupowano je pod kątem podobieństw społeczno-gospodarczych.

## Wykorzystane narzędzia
* Język: R
* Środowisko: RStudio

## Zastosowane metody statystyczne
W pracy wykorzystano następujące metody analizy danych:

1. Porządkowanie liniowe (budowa rankingu):
   * Metoda Hellwiga 
   * Metoda standaryzowanych sum

2. Analiza skupień (grupowanie):
   * Aglomeracyjne grupowanie hierarchiczne (metoda Warda)
   * Algorytm k-średnich (k-means)

3. Walidacja i ocena modeli:
   * Wybór optymalnej liczby klastrów oraz ocena jakości grupowania z wykorzystaniem miary Silhouette (analiza sylwetkowa).

## Zawartość repozytorium
* Skrypty w języku R zawierające kod odpowiedzialny za transformację danych, obliczenia i wizualizację.
* Zbiory danych wejściowych.
* Wygenerowane wykresy (m.in. dendrogramy, wykresy sylwetkowe).
* Raport końcowy podsumowujący wyniki.
