# uniquechoice

- [uniquechoice](#uniquechoice)
  - [Opis projektu](#opis-projektu)
  - [Wybór testów](#wybór-testów)
    - [Testy eksploracyjne](#testy-eksploracyjne)
      - [Defekty](#defekty)
        - [uniquechoice.pl - strona startowa](#uniquechoicepl---strona-startowa)
        - [wyszukiwarka](#wyszukiwarka)
        - [uniquechoice.pl/o-nas/](#uniquechoiceplo-nas)
        - [uniquechoice.pl/sklep/](#uniquechoiceplsklep)
        - [uniquechoice.pl/zamowienie/](#uniquechoiceplzamowienie)
        - [uniquechoice.pl/kawiarnia/](#uniquechoiceplkawiarnia)
        - [uniquechoice.pl/moje-konto/](#uniquechoiceplmoje-konto)
      - [Inne](#inne)

---

## Opis projektu

W projekcie tym zajmę się manualnym testowaniem sklepu internetowego firmy Uniquechoice.pl. Serwis można obejrzec [tutaj](https://uniquechoice.pl. Moim celem nadrzędnym przy realizacji tego projektu jest rozpoczęcie praktyki pracy testera manualnego.

---

## Wybór testów

Testowany serwis jest już online. Nie mam dokumentacji oraz wymagań. Mój budżet jest nieokreślony. Biorąc te fakty pod uwagę decyduję się wykonac dwa rodzaje testów:

- testy eksploracyjne,
- testy funkcjonalne na podstawie scenariuszy użytkownika

### Testy eksploracyjne

#### Defekty

##### uniquechoice.pl - strona startowa

ID|Tytuł|Priorytet|Załącznik
-|-|-|-
001|widoczny kod źródłowy|lowest|[screen](screen1.png)
002|rotator nowości nie wyświetla się prawidłowo, elementy graficzne są rozciągnięte w poziomie|lowest|[screen](screen2.png)
003|formatowanie tekstu w nagłówkach, w kafelkach nowości jest różne, tekst różni się wielkością|lowest|[screen](screen3.png)
004|wysokośc kafelków nowości nie jest jednakowa, strona startowa|lowest|[screen](screen4.png)
005|pomarańczowe tło nagłówków kafelków nowości jest różnego rozmiaru (w pionie)|lowest|[screen](screen4.png)
006|brak nagłówka w kafelku nowości|lowest|[screen](screen5.png)
007|formatowanie obrazków, tekstu oraz przycisków kafelków produktów nie jest spójne|lowest|[screen](screen6.png)
008|przycisk "Dodaj do koszyka" oraz przycisk "Wybierz opcje" mają inny styl|lowest|[screen](screen6.png)
009|wszystkie trzy odnośniki mailto w stopce są wpisane nieprawidłowo|high|[screen](screen7.png)

##### wyszukiwarka

ID|Tytuł|Priorytet|Załącznik
-|-|-|-
010|cytowana fraza wpisana w polu wyszukiwania w wynikach wyszukiwania wykracza poza widzialne pole, jest nie do odczytania|low|[screen](screen8.png)
011|w przypadku nie znalezienia szukanych fraz w wyszukiwarce, komunikat jest wyświetlany w formie przycisku, zamiast tekstu, może byc to mylące dla użytkownika|lowest|[screen](screen9.png)
012|przycisk "Dodaj do koszyka" wychodzi poza obramowanie podglądu wyniku wyszukiwania|lowest|[screen](screen10.png)

##### uniquechoice.pl/o-nas/

ID|Tytuł|Priorytet|Załącznik
-|-|-|-
013|przycisk przewijania kafelków z grafikami wydarzeń, przy których współpracowała firma nie przewija kafelków, przenosi natomiast na dół strony|lowest|[video](video1.gif)

##### uniquechoice.pl/sklep/

ID|Tytuł|Priorytet|Załącznik
-|-|-|-
014|pasek nawigacyjny z przyciskami do przełączania podstron z produktami nie jest widoczny po wejściu do sklepu, pojawia się dopiero kiedy zmienimy sposób sortowania|lowest|[video](video2.gif)
015|pasek ten jest jednocześnie nieużywalny z uwagi na autoładowanie kolejnych produktów, ucieka z pola widzenia|lowest
016|licznik wyświetlonych produktów pokazuje zakres 1-12 niezależnie od ilości wyświetonych produktów, nie aktulizuje się|low|[screen](screen11.png)
017|przycisk "Informacje dodatkowe" na podstronie produktu po wykonaniu akcji nie przenosi do zamierzonej podstrony tylko przenosi na górę strony|low
018|przycisk "Zapytanie ofertowe" w widoku koszyka wywołuje okno, w którym wyświetla się kod źródłowy, akcja jest niemożliwa do wykonania|high|[screen](screen12.png)

##### uniquechoice.pl/zamowienie/

ID|Tytuł|Priorytet|Załącznik
-|-|-|-
019|po kliknięciu w przycisk "Jeżeli masz już konto **Kliknij tutaj, aby się zalogowac**" wyświetla się nieprzetłumaczony tekst|lowest|[screen](screen13.png)
020|automat do resetowania hasła nie weryfikuje czy wpisany adres e-mail jest poprawny, formularz przyjmuje jakąkolwiek wpisaną frazę za wyłączeniem spacji oraz pustego pola|highest|
021|po zaznaczeniu opcji "Chcę fakturę VAT" pole "Nazwa firmy" może pozostac niewypełnione, formularz przyjmuje tak wypełnione zamówienie, nie powinien, to pole powinno byc obowiązkowe|high

##### uniquechoice.pl/kawiarnia/

ID|Tytuł|Priorytet|Załącznik
-|-|-|-
022|komnunikat cookies wyświetla się w miejscu, które jest nieklikalne, jako element tła, jest również przez to zasłonięty przez elementy belki górnej nawigacji|medium|[screen](screen14.png)

##### uniquechoice.pl/moje-konto/

ID|Tytuł|Priorytet|Załącznik
-|-|-|-
023|po zalogowaniu się wyświetla się nieprzetłumaczony tekst|medium|[screen](screen15.png)
024|moje-konto/orders w przypadku braku historii zamówień pokazuje nieprzetłumaczony tekst w polu "Go shop Żadne zamówienie nie zostały jeszcze złożone."|lowest|[screen](screen16.png)
025|email powitalny po założeniu konta jest nieprzetłumaczony|medium|[screen](screen17.png)
026|email zmiany hasła jest nieprzetłumaczony|medium|[screen](screen18.png)
027|zmiany danych konta w podstronie moje-konto/edit-account (szczegóły konta) nie jest możliwa, wyświetlony błąd "Wyświetlana nazwa jest wymaganym polem", takiego pola nie ma w szczegółach konta|high|[screen](screen19.png)
028|komunikat o słabym haśle wyświetla się pomimo spełnienia wszystkich warunków mocnego hasła|lowest|

#### Inne

ID|Tytuł|Priorytet|Załącznik
-|-|-|-
029|komunikat "404 strony nie znaleziono, na podstronie 404 nie wyświetla się prawidłowo, jest zasłonięty przez belkę górną|medium|[video](video3.gif)
030|dwa umieszczone na tej samej podstronie przyciski pojawiają się dopiero po najechaniu na nie kursorem|medium|[video](video3.gif)
