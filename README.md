# challenge_portfolio_Karolina
 
<sub> :blue_heart: Plik zawierający zadania z pierwszego sprintu z DareIT 2023 :blue_heart:

---
## [TASK 1.](#TASK-1) Testy eksploracyjne :zap:
  
### Subtask 1.: Test z teorii :nerd_face:
Wynik: 6/10 pkt :pinching_hand:

### Subtask 2.: Utworzenie repozytorium :books:
Właśnie się w nim znajdujemy :innocent:
  
### Subtask 3.: Słowo wstępu :scroll:
> Dlaczego zdecydowałaś się na udział w challenge portfolio?

Cześć :wave: Mam na imię Karolina. :blonde_woman:

Mam nadzieję nabyć nowe umiejętności dzięki temu challenge'owi oraz wykorzystać swoje cechy - dokładność :jigsaw: , dociekliwość :raised_eyebrow: , spostrzegawczość :mag: - dzięki którym uda mi się sprawniej przebranżowić. M.in. w tym celu tworzę portfolio, które pozwoli mi się wykazać. :woman_technologist:

Zapraszam do przejrzenia mojego portfolio
[<img width="30" alt="Github logo" src="https://user-images.githubusercontent.com/110050632/220699930-d425d600-c30a-499d-8bf9-a713cf389535.png">](https://github.com/karabiel/portfolio) oraz do kontaktu przez portal LinkedIn
[<img width="20" alt="LinkedIn logo" src="https://user-images.githubusercontent.com/110050632/220698295-2aaafcfd-449e-4ebc-8b83-150a4fe3ddac.png">](https://www.linkedin.com/in/karabiel/).

  
### Subtask 4.: Testy eksploracyjne na podstawie strony *[Scouts Panel](https://scouts-test.futbolkolektyw.pl/)*


> Na czym polega ta aplikacja? Do czego służy?

:soccer: Aplikacja *Futbol kolektyw. Platforma skautingowa* służy do zbierania informacji na temat piłkarzy oraz edycja tych informacji, zarówno w języku polskim, jak i angielskim.

Logując się do panelu jako użytkownik, mamy możliwość dodania gracza, meczu oraz raportu czy przeglądanie istniejących rekordów oraz ich edycja.


> Jakie funkcjonalności znajdują się w aplikacji? Do czego służą? Czy są intuicyjne, czy może byś coś zmieniła?

:hammer_and_wrench: Funkcjonalności:
- logowanie do panelu
- przypomnienie hasła do logowania
- zmiana języka polski/angielski
- kontakt z Dev team z pozycji *Scouts panel* - odnośnik do Slack'a
- dodanie gracza z pozycji *Linków pomocniczych*
- przeglądanie dodanych graczy
	- pobranie CSV
	- druk
	- wybranie wyświetlanych kolumn
	- filtrowanie tabeli

Nie wszystko jest intuicyjne, o czym będę pisać później.

  
> Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?


:wink: Strona ogólnie jest bardzo prosta, przejrzysta. Jest wporządku jak dla mnie. Porównując ze stronami gdzie jest zbyt dużo kolorów, dodatków itd. to wolę w tę stronę.


> Czy aplikacja jest intuicyjna?

:disguised_face: Niezbyt. Dodawanie nowego gracza jest dostępne tylko na stronie głównej. Z dodawaniem raportu oraz meczu również jest problem, o czym szerzej piszę poniżej.

  
> Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem?

***Panel logowania*** :key:

- Brak możliwości założenia konta do aplikacji.
- Brak możliwości zmiany hasła konta użytkownika.
- W podstronie *Gracze* oznaczenia ikonek (po najechaniu na nie myszą) nie są przetłumaczone z języka angielskiego na polskiej wersji językowej.
- Dodanie raportu możliwe jest tylko w podstronie *Mecze*, gdy jest dodany przynajmniej jeden mecz - przechodząc ze *Strony głównej* do podstrony *Gracze* przechodzimy do dowolnego gracza, klikając w dowolną informację o danym graczu, w menu bocznym (po lewej stronie), Wybierając w *Raportach* przycisk *Dodaj raport* wyświetla się podstrona *Mecze* zamiast formularza dodawania raportu.


	
**Podstrona *Dodawanie / Edycja gracza*** :standing_man: :standing_person:

- Filtr pozwala odznaczyć wszystkie kolumny (powinien wyświetlać przynajmniej jedną aktywną kolumnę).

- Dodawanie gracza możliwe jest tylko z *Linków pomocniczych* znajdujących się na *Stronie głównej*. Powinna być dostępna opcja dodania gracza w podstronie *Gracze*.

- Wpisując do formularza *Edycja gracza* dane liczbowe w polach *wzrost* i *waga*, system zezwala na wyświetlanie liczb ujemnych oraz abstrakcyjnych (np. 2 cm wzrostu oraz 2000 kg masy ciała).

- W formularzu *Edycji gracza* przycisk *Clear* powoduje cofnięcie wprowadzonych zmian, a nie usunięcie danych ze wszystkich pól, jakby sugerowało to słowo.

- Opcja sortowania nie jest dostępna dla kolumn *Mecze* oraz *Raporty*.

- W obowiązkowe pola (*Imię*, *Nazwisko* oraz *Główna pozycja*) można wpisać dowolne znaki (w tym samą spację) oraz ich ilość nie jest limitowana.

- Pole *Data urodzenia* nie ma limitu, można wybrać datę poniżej 1900 r. i powyżej 2023 r.

- Pole *Numer telefonu* - zezwala na wprowadzenie dowolnych znaków oraz nie ma ograniczenia ilości znaków.

- Pole *E-mail* - nie informuje w czym jest błąd przy wpisywaniu nieprawidłowych wartości (wymagany znak *@*, limit znaków).

- Pole *Link z YouTube* zezwala na wprowadzenie dowolnych znaków, bez sprawdzenia czy jest to URL.

- Przycisk *Dodaj język* - pozwala wprowadzić dowolne znaki lub pozostawić puste pole (powinna być np. rozwijana lista).

- Nie ma możliwości usunięcia dodanego gracza.

- Pole *Profil facebook* można uzupełnić dowolną wartością.

- Pola *Łączy nas piłka* i *90 minut* - nie wiadomo co to znaczy, jakimi danymi je uzupełnić.



Dodatkowo, w angielskiej wersji językowej formularza: :leg:

- Województwa w liście rozwijanej nie są wymienione alfabetycznie.

- Pole *Age* (w angielskiej wersji językowej) powinno być przetłumaczone na *Date of birth*.

- Pole *Leg* nie ma wyjaśnienia, co oznacza.

- Pole *Łączy nas piłka* i *90 minut* nie są przetłumaczone na język polski.



**Podstrona *Dodawanie / Edycja meczu*** :running_man: :runner:

- Pola *Web match* oraz *General* nie są przetłumaczone w polskiej wersji językowej formularza.

- Wybór rodzaju meczu nie jest obowiązkowym polem do zaznaczenia, ale jeśli nic się nie zaznaczy to formularz zaznacza drugą z kolei opcję (*mecz wyjazdowy*), co widać po ponownym wejściu w edycję danego meczu.

- Pole *czas gry* nie ma podanej jednostki (min) oraz nie jest ograniczony do odpowiednich wartości - może zostać wypełniony wartością ujemną, zerem, wartością powyżej 120 (w domyśle - minut).

- W formularzu *Edycja gracza* oraz *Edycja meczu* w języku polskim przyciski *submit* oraz *clear* powinny być przetłumaczone na język polski.


	
**Akcja *rozpocznij mecz*** :stopwatch:

- Podstrona jest nieintuicyjna, nie ma wyjaśnienia w jaki sposób z niej korzystać.

- Można dodawać duże ilości połowy meczu (gdzie w domyśle są tylko dwie).

- Symbol "kosza" nie wykonuje żadnej akcji.

- Brak możliwości edycji wprowadzonych akcji.

- Po kliknięciu w symbol *play* odliczany jest czas - mecz trwa zwykle ok. 90 min.

- Przy dużej ilości dodanych akcji, pole boiska jest nieczytelne.


**Podstrona *Edycja raportu*** :writing_hand:

- W formularzu *Dodawania gracza* województwo nie jest obowiązkowym polem do uzupełnienia, a w momencie dodawania raportu na podstawie meczu pojawia się komunikat, że pole "województwo" danego gracza jest wymagane.

- W formularzu edycji raportu podpowiedź do pola *Inteligencja boiskowa* w pierwszym zdaniu jest użyty podwójnie ukośnik, a kilka słów dalej zabrakło jednego z nich (rozdzielenie słów *piłki* od *Ocena*).

- W podpowiedzi do pola *Mentalność* w dwóch ostatnich zdaniach brakuje znaków interpunkcyjnych - kropki na końcu przedostatniego zdania oraz znaku zapytania na końcu ostatniego zdania.

- W podpowiedzi do pola "Recenzja" pierwsze zdanie ("Wybieramy 1 spośród poniższych punktów") jedynka powinna być zapisana słownie, aby nie wprowadzać w błąd przy ocenie w skali 1-5. Dodatkowo formularz pozwala zaznaczyć połowę "gwiazdki".

- Formularz pozwala zapisywać niewypełnione wszystkie pola.

- Formularz pozwala zostawić komentarze z samymi spacjami.

- Nieprawidłowo działa opcja wypunktowania listy - w przypadku próby dodania kolejnej pozycji do stworzonej listy, nie pojawia się przy niej kolejny symbol - kropka lub cyfra w przypadku listy numerowanej.

- Zaznaczając jedno z kilku słów i wybierając aby było zapisane kursywą, przechyla się również słowo znajdujące się w tej samej linijce przed oraz po wybranym słowie.

- Przechodząc z wypełnianego formularza użytkownik nie zostaje zapytany, czy na pewno chce porzucić wprowadzane informacje.


### Subtask 5.: Jira (zadanie dodatkowe) :star:

<br>

---
## [TASK 2.](#TASK-2) Test cases :computer:
***Na podstawie strony [Scouts Panel](https://scouts-test.futbolkolektyw.pl/).***
  
### Subtask 1.: Pisanie przypadków testowych na podstawie User Story :couple:
:link: [Task 2. Subtask 1.](https://docs.google.com/document/d/16axYt9oWGVhoxJG_qsYtjMcE5DUH_8Lb6Pc2V6E4WtQ/edit?usp=sharing)


### Subtask 2.: Pisanie przypadków testowych na podstawie :sparkles: własnych doświadczeń :sparkles:
:link: [Task 2. Subtask 2.](https://docs.google.com/document/d/1GMdhsz729eZkyM9er0wHh-U1uyYDE_b8DTaAOpzDUXg/edit)


### Subtask 3.: Po co piszemy test case’y? :thinking:
- poprawne napisanie TC pozwala w większym stopniu zapobiegać defektom -> oszczędność pieniędzy na ewentualnych poprawkach

- sprawdzenie czy wybrana ścieżka programu spełnia dane wymagania -> budowanie zaufania do produktu końcowego


### Subtask 4.: Dla chętnych :star2:
Jestem chętna do zrobienia tego zadania, ściągnęłam nawet tamtą aplikację (*Pick Eat Up*), ale jeszcze nie napisałam do niej TC. Za jakiś czas to uzupełnię. 

<br>

---
## [TASK 3.](#TASK-3) Raportowanie błędów
***Na podstawie strony [Panel Skautingowy](https://scouts.futbolkolektyw.pl/).***

### Subtask 1.: Bug report template :lady_beetle:
:link: [Task 3. Subtask 1.](https://docs.google.com/document/d/1djLZ09u_bKfx9MLl1AxAG-ykcWMUVo546pexBoXBvAo/edit)

### Subtask 2.: Bug report :space_invader:
:link: [Task 3. Subtask 2.](https://docs.google.com/document/d/1fc_X-yDKoup5dAW1CryDtON9PDTs1DBv-mdBZgsI9uk/edit)
  
### Subtask 3.: Test report :chart_with_upwards_trend:
:link: [Task 3. Subtask 3.](https://docs.google.com/document/d/1KBOfmVwDDewuCNtc_5K7XHYyNXzRtOEJ_VUHEgW1zSM/edit)

<br>

---
## [TASK 4.](#TASK-4) Testowanie aplikacji mobilnych :iphone:
***Na podstawie aplikacji [OLX](https://play.google.com/store/apps/details?id=pl.tablica&hl=pl&gl=US) v. 5.77.0***

### Subtask 1.: Formatka do zgłaszania błędów systemu :memo:

:link: [Task 4. Subtask 1.](https://docs.google.com/document/d/1vt3dzxLDdNeluTY2paLiySLEmWjmvrv8LjWzXWVNItw/edit)

### Subtask 2.: Testowanie eksploracyjne i raportowanie błędów :dizzy:

:link: [Task 4. Subtask 2.](https://docs.google.com/document/d/10Z9YXiHvSQIUTTH_gE_tWjCFvfwflCbufErSiO5BM9w/edit)
 
### Subtask 3.: Aplikacja OLX :shopping:

> Do czego służy ta aplikacja? Jaki jest cel tej aplikacji? :shopping_cart:

Aplikacja OLX służy do dodawania / edycji / usuwania ogłoszeń (jako autor), przeglądania i zapisu ogłoszeń (jako nabywca) oraz kontaktowanie się z autorami.

Ma funkcje m.in.:
- utwórz konto do aplikacji - przez adres e-mail, konto na Facebook'u, konto Apple, konto Google,
- zaloguj jako użytkownik prywatny / firma - jw.,
- utwórz ogłoszenie - sprzedaj / oddaj za darmo / wymień / wypożycz,
- edytuj ogłoszenie,
- odśwież ogłoszenie,
- promuj ogłoszenie,
- zakończ utworzone ogłoszenia,
- przeglądaj dodane ogłoszenia,
- dodaj filt wyszukiwania ogłoszeń do *obserwowanych*,
- dodaj ogłoszenie do *obserwowanych*,
- napisz wiadomość do autora ogłoszenia,
- skontaktuj się z autorem ogłoszenia poprzez podany numer telefonu,
- oceń transakcję,
- przesyłki - sprzedajesz, kupujesz, dane do wypłat,
- płatności (portfel),
- zgłoś naruszenie ogłoszenia,
- zmień ustawienia - edytuj konto (imię, adres e-mail, hasło), powiadomienia, tryb jasny/ciemny,
- wyloguj się,
- usuń konto.


> Kto ma być użytkownikiem końcowym aplikacji? :detective:

Osoby prywatne, które dokonują transakcji na odległość lub osobiście, wymieniają się rzeczami, sprzedają je lub oddają, od innych osób prywatnych lub firm.
Powinna to być raczej osoba dorosła, która w minimalnym stopniu potrafi posługiwać się telefonem z dostępem do Internetu. Bez znaczenia jakiej płci, w jakim wieku (chociaż raczej osoby pełnoletnie), z jakiego miejsca - z miasta czy ze wsi (jest możliwość odbioru osobistego czy wysyłka), bez dodatkowych kosztów za prowadzenie podstawowego konta, ale z możliwością wykupienia np. promowania ogłoszenia.


> Czy według Ciebie aplikacja jest user-friendly? :teddy_bear:

Raczej tak. Chociaż często zmieniają się kategorie i regulamin strony co może po jakimś czasie korzystania irytować.
Główna strona szybko się ładuje. Nawigacja po stronie jest raczej intuicyjna. Treści znajdujące się w aplikacji są w przejrzysty sposób prezentowane - miniatura ogłoszenia (zdjęcie, tytuł, cena, orientacyjne miejsce, data opublikowania) jak i samo ogłoszenie.
Plusem dla mnie na pewno jest możliwość zmiany trybu z jasnego na ciemny (i odwrotnie również oczywiście) :flashlight:.


> Jak byś usprawniła aplikację? Co byś w niej poprawiła? Czy masz jakiś pomysł na dodatkową funkcjonalność? :bulb:

Ogólnie aplikacja jest raczej intuicyjna. Podczas testowania znalazłam kilka rzeczy, które podczas codziennego korzystania nie były dla mnie istotne lub nie natrafiłam na nie.
Zablokowałabym niektóre opcje, np. filtrując wyszukiwania ogłoszeń z kategorii *Oddam za darmo* żeby nie można było wpisać zakresu cen.
Przy wprowadzeniu opisu na 9000 znaków (taki jest podany limit) nie powinno być możliwości wprowadzenia kolejnych znaków - aktualnie można było wprowadzić przed przynajmniej ostatnim znakiem, który był następnie zastępowany.


> Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej :desktop_computer: , a natywnej? :iphone:

Testowanie aplikacji natywnej jest bardziej ograniczone (sprzętowo) - nie ma możliwości zmiany środowiska testowania, jak w przypadku testowania aplikacji internetowej, gdzie można dowoli zmieniać systemy operacyjne, przeglądarki internetowe itd.
Na komputerze można emulować telefon czy tablet, w drugą stronę jest to co najmniej uciążliwe.

<br>

---
## [TASK 5.](#TASK-5) SQL part 1. :heart_decoration:

### Subtask 1: Krótki kurs podstaw SQL
*Operatory/zapytania jakich się nauczyłam* :brain:

SQL queries:
- SELECT (some data from database) :point_right: ,
- CREATE (table) :magic_wand: ,
- DELETE (some records in the table) :wastebasket: ,
- DROP (delete column / table / DB with all values) :skull_and_crossbones:,
- UPDATE (some data) :muscle: ,
- INSERT INTO (new rows in the table) :new:,
- ORDER BY ('ASC' - ascending :arrow_upper_right: / 'DESC' - descending order :arrow_lower_right:).

Operators:
- arithmetic
  - ADD :heavy_plus_sign: / SUBTRACT :heavy_minus_sign:,
  - MULTIPLY :heavy_multiplication_x: / DIVIDE :heavy_division_sign: ,
  - AVG (average) :signal_strength: ,
  - COUNT (number of rows) :abacus: ,
  - MAX :arrow_up: / MIN :arrow_down: ,
  - SUM **=** ;

- comparison
  - '='  - EQUAL TO,
  - '>'  - GREATER THAN,
  - '<'  - LESS THAN,
  - '>=' - GREATER THAN OR EQUAL TO,
  - '<=' - LESS THAN OR EQUAL TO,
  - '<>' - NOT EQUAL TO;

- logical
  - AND,
  - BETWEEN,
  - LIKE,
  - NOT,
  - OR.

### Subtask 2.: Konfigurowanie środowiska i wgranie bazy danych :card_index_dividers:
*Instalacja programu Xampp i pobranie przygotowanej bazy danych (dot. sklepiku z filmami).*

### Subtask 3.: Zadania :weight_lifting:
> Zad. 1. Wyświetl tabelę actors w kolejności alfabetycznej sortując po kolumnie surname.

Użyte zapytanie:
```SQL
SELECT * FROM actors ORDER BY surname;
```
Wynik zapytania:

<img width="182" alt="Screenshot_20230213_023956" src="https://user-images.githubusercontent.com/110050632/218533719-af40052c-e7a2-408f-98f0-2fb81c91f191.png">


> Zad. 2. Wyświetl film, który powstał w 2019 roku.

Użyte zapytanie:
```SQL
SELECT * FROM movies WHERE year_of_production = '2019';

```
Wynik zapytania:

<img width="237" alt="Screenshot_20230213_110426" src="https://user-images.githubusercontent.com/110050632/218595652-6fcc8329-4908-4386-9c18-7d554c04a8e1.png">


> Zad. 3. Wyświetl wszystkie filmy, które powstały między 1900, a 1999 rokiem.

Użyte zapytanie:
```SQL
SELECT * FROM movies WHERE year_of_production BETWEEN 1990 AND 1999;

```
Wynik zapytania:

<img width="237" alt="Screenshot_20230213_111819" src="https://user-images.githubusercontent.com/110050632/218595788-71249e73-51a4-4c70-a5f8-e6371a631801.png">


> Zad. 4. Wyświetl JEDYNIE tytuł i cenę filmów, które kosztują poniżej 7$.

Użyte zapytanie:
```SQL
SELECT title, price FROM movies WHERE price < 7;
```
Wynik zapytania:

<img width="215" alt="Screenshot_20230213_112134" src="https://user-images.githubusercontent.com/110050632/218595984-b92b4ffe-4381-464f-a423-67c36e6c0bb0.png">


> Zad. 5. Użyj operatora logicznego AND, aby wyświetlić aktorów o actor_id pomiędzy 4-7 (bez użycia operatora BETWEEN).

Użyte zapytanie:
```SQL
SELECT * FROM actors WHERE actor_id >= 4 AND actor_id <= 7;
```
Wynik zapytania:

<img width="171" alt="Screenshot_20230213_112749" src="https://user-images.githubusercontent.com/110050632/218596192-eea5ec0a-3ecf-4260-960f-d8529996a123.png">


> Zad. 6. Wyświetl klientów o id 2, 4, 6 wykorzystaj do tego warunek logiczny.

Użyte zapytanie:
```SQL
SELECT * FROM customers WHERE customer_id IN (2, 4, 6);
```
Wynik zapytania:


<img width="260" alt="Screenshot_20230214_121020" src="https://user-images.githubusercontent.com/110050632/218596910-9b8b6b64-4b8f-4b79-b922-7e6cd0410d0d.png">


> Zad. 7. Wyświetl klientów o id 1, 3, 5 wykorzystaj do tego operator IN.

Użyte zapytanie:
```SQL
SELECT * FROM customers WHERE customer_id IN (1, 3, 5);
```
Wynik zapytania:

<img width="250" alt="Screenshot_20230213_113039" src="https://user-images.githubusercontent.com/110050632/218596337-3244af27-5eb4-43e1-a24f-1135e76686c4.png">


> Zad. 8. Wyświetl dane wszystkich osób z tabeli ‘actors’, których imię zaczyna się od ciągu “An”.

Użyte zapytanie:
```SQL
SELECT * FROM actors WHERE name LIKE 'An%';
```
Wynik zapytania:

<img width="152" alt="Screenshot_20230213_113513" src="https://user-images.githubusercontent.com/110050632/218596506-30cc4cd3-961f-43b6-9bbd-fcd93923658d.png">


> Zad. 9. Wyświetl dane klienta, który nie ma podanego adresu email.

Użyte zapytanie:
```SQL
SELECT * FROM customers WHERE email IS NULL;
```
Wynik zapytania:

<img width="209" alt="Screenshot_20230213_113702" src="https://user-images.githubusercontent.com/110050632/218596652-3a97bf93-8f9b-496e-8540-0ec472bb2164.png">


> Zad. 10. Wyświetl wszystkie filmy, których cena wynosi powyżej 9$ oraz ich ID mieści się pomiędzy 2 i 8 movie_id.

Użyte zapytanie:
```SQL
SELECT * FROM movies WHERE price > 9 AND movie_id BETWEEN 2 AND 8;
```
Wynik zapytania:


<img width="261" alt="Screenshot_20230213_113920" src="https://user-images.githubusercontent.com/110050632/218596768-cdc53fe8-6d4b-4eb0-8563-282515d2fd5c.png">

<br>

---
## [TASK 6.](#TASK-6) SQL part 2. :heart_decoration:

### Subtask 1: Krótki kurs podstaw SQL cz.2
Zadania :weight_lifting:


> Zad. 11. Zamień nazwisko Ani Muler na Miler.

Użyte zapytanie:
```SQL
UPDATE customers SET surname='Miler' WHERE customer_id=3;
```
Wynik zapytania:

<img width="261" alt="Table 11" src="https://user-images.githubusercontent.com/110050632/220184793-e55bf9c1-0541-4afa-af95-c83912c52f3a.png">



>Zad. 12. Pobrałam za dużo pieniędzy od klienta, który kupił w ostatnim czasie film o id 4. Korzystając z funkcji *join* sprawdź, jak ma na imię klient i jakiego ma maila. W celu napisania mu wiadomości o pomyłce fantastycznej szefowej. 

Użyte zapytanie:
```SQL
SELECT customers.name, customers.email, sale.movie_id
FROM customers
INNER JOIN sale 
ON customers.customer_id=sale.customer_id;

```
Wynik zapytania:

<img width="204" alt="Table 12" src="https://user-images.githubusercontent.com/110050632/220189071-94e6e4e5-e948-4613-b4bf-52628e2baf12.png">

Stratnym klientem jest Katia :cry:


> Zad. 13. Uzupełnij e-mail klientce Patrycji wpisując: pati@mail.com.

Użyte zapytanie:
```SQL
UPDATE customers SET email='pati@mail.com' WHERE customer_id=4;

```
Wynik zapytania:

<img width="261" alt="Table 13" src="https://user-images.githubusercontent.com/110050632/220189980-f254f720-79d9-46fc-9c54-46bdc4918332.png">


>Zad. 14. Dla każdego zakupu wyświetl, imię i nazwisko klienta, który dokonał zakupu oraz tytuł zakupionego filmu, wykorzystaj do tego funkcję inner join.
	
Użyte zapytanie:
```SQL
SELECT customers.name, customers.surname, movies.title
FROM movies, customers
INNER JOIN sale ON customers.customer_id=sale.customer_id;
```
Wynik zapytania:

<img width="261" alt="Table 13" src="https://user-images.githubusercontent.com/110050632/220423545-7cb1a96a-a4e3-45cf-9554-88a74ce67db0.png">


> Zad. 15. W celu anonimizacji danych, chcesz stworzyć pseudonimy swoich klientów. Dodaj kolumnę o nazwie *pseudonym* do tabeli customers. Wypełnij kolumnę w taki sposób, aby pseudonim stworzył się z dwóch pierwszych liter imienia i ostatniej litery nazwiska - np. Natalie Pilling → Nag

Użyte zapytania:
```SQL
ALTER TABLE customers
ADD COLUMN pseudonym VARCHAR(3);
```

```SQL
Update customers
SET pseudonym = Concat (LEFT (name, 2), RIGHT(surname, 1));
```

Wynik zapytania:

<img width="261" alt="Table 15" src="https://user-images.githubusercontent.com/110050632/220442391-45554bc7-65a2-408b-a9b0-f6d7f864785c.png">


> Zad. 16. Wyświetl tytuły filmów, które zostały zakupione, wyświetl tabelę w taki sposób, aby tytuły się nie powtarzały. 

Użyte zapytanie:
```SQL
SELECT DISTINCT movies.title
FROM movies
INNER JOIN sale ON sale.movie_id = movies.movie_id ORDER BY title;
```
Wynik zapytania:

<img width="204" alt="Table 16" src="https://user-images.githubusercontent.com/110050632/220453812-b996e3db-159f-4657-9719-a62bc2da4d60.png">


> Zad. 17. Wyświetl wspólną listę imion wszystkich aktorów i klientów, a wynik uporządkuj alfabetycznie. Wykorzystaj do tego funkcję *UNION*.

Użyte zapytanie:
```SQL
SELECT name FROM actors
UNION
SELECT name FROM customers
ORDER BY name;
```
Wynik zapytania:

<img width="95" alt="Table 17" src="https://user-images.githubusercontent.com/110050632/220455326-5bbea533-0582-484d-baeb-5f7651644d34.png">


> Zad. 18. Polskę opanowała inflacja i nasz sklepik z filmami również dotknął ten problem. Podnieś cenę wszystkich filmów wyprodukowanych po 2000 roku o 2,5$. 

Użyte zapytanie:
```SQL
UPDATE movies
SET price = price + 2.5 WHERE year_of_production>2000;
```
Wynik zapytania:

<img width="261" alt="Table 18" src="https://user-images.githubusercontent.com/110050632/220458479-acb05d30-a453-479a-8da2-01d6c8a2ab02.png">


> Zad. 19. Wyświetl imię i nazwisko aktora o id 4 i tytuł filmu, w którym zagrał.

Użyte zapytanie:
```SQL
SELECT actors.name, actors.surname, movies.title
FROM ((cast
INNER JOIN actors ON cast.actor_id = actors.actor_id)
INNER JOIN movies ON cast.movie_id = movies.movie_id) WHERE cast.actor_id=4;
```
Wynik zapytania:

<img width="206" alt="Table 19" src="https://user-images.githubusercontent.com/110050632/220466907-29614d09-1675-4931-90c2-018d53bcf9ff.png">
	
	
> Zad. 20. Dodaj do tabeli customers nową krotkę, gdzie customer_id = 7, name= Honia, surname = Stuczka-Kucharska, email = honia@mail.com oraz pseudonym = Hoa.

Użyte zapytanie:
```SQL
INSERT INTO customers
VALUES (7, 'honia@mail.com', 'Honia', 'Hoa', 'Stuczka-Kucharska');
```
Wynik zapytania:

<img width="261" alt="Table 20" src="https://user-images.githubusercontent.com/110050632/220468889-3773c34f-054b-43a4-b2b8-227e5213f247.png">


### Subtask 2.: Test z ISTQB

Wynik z zestawu [ECRU](http://getistqb.com/quiz-ecru/): 12/15 pkt :trophy:

### Subtask 3.: Tworzymy portfolio
:fire: [Link do portfolio](https://github.com/karabiel/portfolio) :fire:

	
<br>

Jesteś na samym dole strony, a potrzebujesz coś z samej góry? Z pomocą przychodzi ta oto niepozorna drabinka
[:cloud: :ladder: :cloud:](#challenge_portfolio_Karolina)<a name="challenge_portfolio_Karolina"></a> 
