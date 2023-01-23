 # challenge_portfolio_Karolina
 
<sub> Plik zawierający zadania z pierwszego sprintu z DareIT 2023 :innocent:
  
## [TASK 1](#TASK-1)
  
### Subtask 1: 6/10 pkt
  
### ~~Subtask 2: ***?***~~
  
### Subtask 3:
> Dlaczego zdecydował_ś się na udział w challenge portfolio?

Mam na imię Karolina.
Mam nadzieję nabyć nowe umiejętności dzięki temu challenge'owi oraz wykorzystać swoje cechy - dokładność, dociekliwość, spostrzegawczość - dzięki którym uda mi się sprawniej przebranżowić. M.in. w tym celu tworzę portfolio, które pozwoli mi się wykazać.

  
### Subtask 4: Testy eksploracyjne na podstawie [tej strony](https://url6405.circle.so/ls/click?upn=kwbwkXnZT32McfWCrnlzohrrzmJl0FdCrPNYFeExGRupuKOWxL3SRDijXgSLkpsWkAYFbk-2FbK4pd3TjJ2LtD4g-3D-3Dhwhr_U5Lv1wU5VRexpMaNRwFFyodbZkCZw8GlxZFvBQlnFrNGc6W9hqNpURZYqqBeLvdEDkKNUnHlYdA4C938wTn1DI3XamE-2FHVs5dolvXKj6piyN1PwIsrbNT7RIN6S1F5pTUb0c3wWBTwktEiLA7Lwkap72KuINBVRqLrrt6DrtmlDa6K2Dk8ONWql0E6Qra-2FaAFtNUagm0PevgK6WHeLiv9w-3D-3D)


> 4.1 Na czym polega ta aplikacja? Do czego służy?

Aplikacja *Futbol kolektyw. Platforma skautingowa* służy do zbierania informacji na temat piłkarzy oraz edycja tych informacji, zarówno w języku polskim, jak i angielskim.

Logując się do panelu jako użytkownik, mamy możliwość dodania gracza, meczu oraz raportu czy przeglądanie istniejących rekordów oraz ich edycja.


> 4.2 Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a?

Funkcjonalności:
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

  
> 4.3 Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?


Strona ogólnie jest prosta, przejrzysta. Jest wporządku jak dla mnie.


> 4.4 Czy aplikacja jest intuicyjna?

Niezbyt. Dodawanie nowego gracza jest dostępne tylko na stronie głównej. Z dodawaniem raportu oraz meczu również jest problem, o czym szerzej piszę poniżej.

  
> 4.5 Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem?

***Panel logowania***

- Brak możliwości założenia konta do aplikacji.
- Brak możliwości zmiany hasła konta użytkownika.
- W podstronie *Gracze* oznaczenia ikonek (po najechaniu na nie myszą) nie są przetłumaczone z języka angielskiego na polskiej wersji językowej.
- Dodanie raportu możliwe jest tylko w podstronie *Mecze*, gdy jest dodany przynajmniej jeden mecz - przechodząc ze *Strony głównej* do podstrony *Gracze* przechodzimy do dowolnego gracza, klikając w dowolną informację o danym graczu, w menu bocznym (po lewej stronie), Wybierając w *Raportach* przycisk *Dodaj raport* wyświetla się podstrona *Mecze* zamiast formularza dodawania raportu.


	
**Podstrona *Dodawanie / Edycja gracza***

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



Dodatkowo, w angielskiej wersji językowej formularza:

- Województwa w liście rozwijanej nie są wymienione alfabetycznie.

- Pole *Age* (w angielskiej wersji językowej) powinno być przetłumaczone na *Date of birth*.

- Pole *Leg* nie ma wyjaśnienia, co oznacza.

- Pole *Łączy nas piłka* i *90 minut* nie są przetłumaczone na język polski.



**Podstrona *Dodawanie / Edycja meczu***

- Pola *Web match* oraz *General* nie są przetłumaczone w polskiej wersji językowej formularza.

- Wybór rodzaju meczu nie jest obowiązkowym polem do zaznaczenia, ale jeśli nic się nie zaznaczy to formularz zaznacza drugą z kolei opcję (*mecz wyjazdowy*), co widać po ponownym wejściu w edycję danego meczu.

- Pole *czas gry* nie ma podanej jednostki (min) oraz nie jest ograniczony do odpowiednich wartości - może zostać wypełniony wartością ujemną, zerem, wartością powyżej 120 (w domyśle - minut).

- W formularzu *Edycja gracza* oraz *Edycja meczu* w języku polskim przyciski *submit* oraz *clear* powinny być przetłumaczone na język polski.


	
**Akcja *rozpocznij mecz***

- Podstrona jest nieintuicyjna, nie ma wyjaśnienia w jaki sposób z niej korzystać.

- Można dodawać duże ilości połowy meczu (gdzie w domyśle są tylko dwie).

- Symbol "kosza" nie wykonuje żadnej akcji.

- Brak możliwości edycji wprowadzonych akcji.

- Po kliknięciu w symbol *play* odliczany jest czas - mecz trwa zwykle ok. 90 min.

- Przy dużej ilości dodanych akcji, pole boiska jest nieczytelne.


**Podstrona *Edycja raportu***

- W formularzu *Dodawania gracza* województwo nie jest obowiązkowym polem do uzupełnienia, a w momencie dodawania raportu na podstawie meczu pojawia się komunikat, że pole "województwo" danego gracza jest wymagane.

- W formularzu edycji raportu podpowiedź do pola *Inteligencja boiskowa* w pierwszym zdaniu jest użyty podwójnie ukośnik, a kilka słów dalej zabrakło jednego z nich (rozdzielenie słów *piłki* od *Ocena*).

- W podpowiedzi do pola *Mentalność* w dwóch ostatnich zdaniach brakuje znaków interpunkcyjnych - kropki na końcu przedostatniego zdania oraz znaku zapytania na końcu ostatniego zdania.

- W podpowiedzi do pola "Recenzja" pierwsze zdanie ("Wybieramy 1 spośród poniższych punktów") jedynka powinna być zapisana słownie, aby nie wprowadzać w błąd przy ocenie w skali 1-5. Dodatkowo formularz pozwala zaznaczyć połowę "gwiazdki".

- Formularz pozwala zapisywać niewypełnione wszystkie pola.

- Formularz pozwala zostawić komentarze z samymi spacjami.

- Nieprawidłowo działa opcja wypunktowania listy - w przypadku próby dodania kolejnej pozycji do stworzonej listy, nie pojawia się przy niej kolejny symbol - kropka lub cyfra w przypadku listy numerowanej.

- Zaznaczając jedno z kilku słów i wybierając aby było zapisane kursywą, przechyla się również słowo znajdujące się w tej samej linijce przed oraz po wybranym słowie.

- Przechodząc z wypełnianego formularza użytkownik nie zostaje zapytany, czy na pewno chce porzucić wprowadzane informacje.



### Subtask 5: Jira (zadanie dodatkowe)
Zostałam dodana do zespołu Justyny oraz Oliwii :sweat_smile:


## [TASK 2](#TASK-2)
  
### Subtask 1: Pisanie przypadków testowych na podstawie User Story.
[Link do pliku z Subtask 1](https://docs.google.com/document/d/16axYt9oWGVhoxJG_qsYtjMcE5DUH_8Lb6Pc2V6E4WtQ/edit?usp=sharing)


### Subtask 2: Pisanie przypadków testowych na podstawie “własnych doświadczeń".
[Link do pliku z Subtask 2](https://docs.google.com/document/d/1GMdhsz729eZkyM9er0wHh-U1uyYDE_b8DTaAOpzDUXg/edit)


### Subtask 3: Po co piszemy test case’y?
//opis możliwości
-poprawne napisanie TC pozwala w większym stopniu zapobiegać defektom -> oszczędność pieniędzy na ewentualnych poprawkach -> budowanie zaufania do produktu końcowego -> 
-sprawdzenie czy wybrana ścieżka programu spełnia dane wymagania


### Subtask 4: zad. z gwiazdką
