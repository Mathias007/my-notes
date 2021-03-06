# My Notes (Notes)

Projekt aplikacji do robienia notatek, zbudowany w oparciu o HTML, CSS i JS.

## Opis

Kliknięcie przycisku **Dodaj** powoduje otwarcie się formularza, w którym możemy wprowadzić dane nowej notatki. Kategorię, od której zależy kolor notatki, wybieramy z listy rozwijanej (demo zawiera trzy kategorie), natomiast jej zawartość wpisujemy w pole tekstowe i zatwierdzamy przyciskiem **Zapisz**. Usunięcie pojedynczej notatki następuje poprzez naciśnięcie znaku "X" w prawym górnym rogu danego elementu. Istnieje także możliwość resetu aplikacji z użyciem buttona **Usuń wszystkie**.

Projekt wykorzystuje `Flexboxa`, `Google Font`, `Font Awesome`.

## Zastosowanie i plany rozwoju

Narzędzie przydatne do planowania rzeczy do wykonania w krótkich odstępach czasu, jednak wymaga rozwoju. Wersja właściwa powinna zawierać:

-   zapisywalność notatek w **localStorage**,
-   możliwość **edycji notatek**,
-   opcję **personalizacji kategorii**, włącznie z ich kolorystyką,
-   możliwość **przenoszenia notatek** w obrębie desktopu aplikacji (`drag and drop`).

Do rozważenia także zastąpienie w js atrybutu innerHTML wytworzeniem poszczególnych elementów nowej notatki (createElement, append).

Preview dostępne:

-   [na serwerze GitHuba](https://mathias007.github.io/my-notes/)
-   [na serwerze własnym (eGildia Graczy)](https://egildia.pl/projects/my-notes/)
