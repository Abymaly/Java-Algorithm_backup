Zasadniczo wszystkie algorytmy sortowania rozpatruje się w aspekcie złożoności obliczeniowej

Ale są też aspekty wynikające z wymagań niefunkcjonalnych:
- czy sortujemy dane które są częściowo posortowane?
- czy sortujemy coś co jest w ogóle nieposrotowane;
- czy to są struktury danych dla których najbardziej skuteczny jest jakiś konkretny algorytm sortowania?
    - dla niektórych struktur danych najlepsze będą algorytymy z zamianą miejsc;
    - dla list najlepsze będzie coś ze wstawianiem;
- czy mamy do dyspozycji procesor wielordzeniowy?

Do zapamiętania:
- _quick sort_ - bo zazwyczaj jest najlepsze;
- _bubble sort_ - bo jest najkrótsze do napisania;

**Sortowanie bąbelkowe** (_bubble sort_):
- mamy tablicę danych;
- bierzemy pierwszą parę elementów, porównujemy je ze sobą i mniejszy przesuwamy na początek;
- przesuwamy się o jeden element, bierzemy kolejną parę i porównujemy;
- złożoność obliczeniowa: O(n^2);
- to jest algorytm o mniej-więcej stałym koszcie sortowania, ale jeśli dane są wstępnie posortowane, to wtedy trzeba wykonać mniej zamian miejsc;
- można trochę uprościć - po pierwszym przelocie największy element jest na końcu tablicy, więc przy kolejnym obrocie można lecieć do n-1. W kolejnym obrocie n-2. Idt.
    - wtedy złożoność obliczeniowa: O((n^2)/2)

