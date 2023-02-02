# uniquechoice

- [uniquechoice](#uniquechoice)
  - [Opis projektu](#opis-projektu)
  - [Wybór testów](#wybór-testów)
    - [Testy eksploracyjne](#testy-eksploracyjne)
      - [Wnioski](#wnioski)

---

## Opis projektu

W projekcie tym zajmę się manualnym testowaniem sklepu internetowego firmy Coffeedesk. Serwis można obejrzec [tutaj](https://www.coffeedesk.pl).

## Wybór testów

Testowany serwis jest już online. Nie mam dokumentacji oraz wymagań. Mój budżet jest nieokreślony. Biorąc te fakty pod uwagę decyduję się wykonac dwa rodzaje testów:

- testy eksploracyjne,
- testy funkcjonalne na podstawie scenariuszy użytkownika

### Testy eksploracyjne

#### Wnioski

1. Defekty, strona startowa.

- widoczny kod źródłowy:
  
![screen](https://github.com/matysekprzemek/uniquechoice/blob/daaa2069a3afcea5ff1ccf93a2f88cced218650b/Zrzut%20ekranu%202023-02-1%20o%2015.31.44.png)

- rotator nowości nie wyświetla się prawidłowo, elementy graficzne są rozciągnięte w poziomie:

![screen](https://github.com/matysekprzemek/uniquechoice/blob/683d123e695b9f7209ca65717c762018d5b1dba4/Zrzut%20ekranu%202023-02-1%20o%2016.38.25.png)

- formatowanie tekstu w nagłówkach, w kafelkach nowości jest różne, tekst różni się wielkością:

![screen](https://github.com/matysekprzemek/uniquechoice/blob/04fa3c56a949056012dca785dd4ed7a15a6ea33e/Zrzut%20ekranu%202023-02-1%20o%2016.59.45.png)

- wysokośc kafelków nowości nie jest jednakowa, strona startowa,
- pomarańczowe tło nagłówków kafelków nowości jest różnego rozmiaru (w pionie):
  
![screen](https://github.com/matysekprzemek/uniquechoice/blob/471110319ac59ca8b3dbe087439fd665e1022397/Zrzut%20ekranu%202023-02-2%20o%2010.54.29.png)

- brak nagłówka w kafelku nowości:

![screen](https://github.com/matysekprzemek/uniquechoice/blob/8f82434295adab4f279d603634481b6e9c3535ed/Zrzut%20ekranu%202023-02-2%20o%2011.04.00.png)

- formatowanie obrazków, tekstu oraz przycisków kafelków produktów nie jest spójne,
- przycisk "Dodaj do koszyka" oraz przycisk "Wybierz opcje" mają inny styl:

![screen](https://github.com/matysekprzemek/uniquechoice/blob/a04717f2d6830dcf1cae30b9ac47332e3191f3a3/Zrzut%20ekranu%202023-02-2%20o%2011.06.54.png)

- wszystkie trzy odnośniki mailto w stopce są wpisane nieprawidłowo:

![screen](https://github.com/matysekprzemek/uniquechoice/blob/349ac8231d4917bb152895e567463bb2b4fc8c38/Zrzut%20ekranu%202023-02-2%20o%2011.29.05.png)

2. Defekty, wyszukiwarka.

- cytowana fraza wpisana w polu wyszukiwania w wynikach wyszukiwania wykracza poza widzialne pole, jest nie do odczytania:

![screen](https://github.com/matysekprzemek/uniquechoice/blob/0d8f0701a19b40509cbfb5e08cdb7e0e6a115e3b/Zrzut%20ekranu%202023-02-2%20o%2011.56.33.png)

- w przypadku nie znalezienia szukanych fraz w wyszukiwarce, komunikat jest wyświetlany w formie przycisku, zamiast tekstu, może byc to mylące dla użytkownika:

![screen](https://github.com/matysekprzemek/uniquechoice/blob/c3db277d3bf778ea4f9e427bc87e10d31ad5fa10/Zrzut%20ekranu%202023-02-2%20o%2012.01.34.png)

- przycisk "Dodaj do koszyka" wychodzi poza obramowanie podglądu wyniku wyszukiwania:

![screen](uniquechoice/Zrzut ekranu 2023-02-2 o 12.06.29.png)
