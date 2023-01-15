# challenge_portfolio_Karolina
<sub> Plik zawierający zadania z pierwszego sprintu z DareIT 2023
  
## [TASK 1](#TASK-1)
  
### Subtask 1: 6/10
  
### Subtask 2: ***?***
  
### Subtask 3: [Odpowiedź na pytanie / cel, oczekiwania od projektu]
> Dlaczego zdecydował_ś się na udział w challenge portfolio
  
### Subtask 4: Testy eksploracyjne na podstawie [tej strony](https://url6405.circle.so/ls/click?upn=kwbwkXnZT32McfWCrnlzohrrzmJl0FdCrPNYFeExGRupuKOWxL3SRDijXgSLkpsWkAYFbk-2FbK4pd3TjJ2LtD4g-3D-3Dhwhr_U5Lv1wU5VRexpMaNRwFFyodbZkCZw8GlxZFvBQlnFrNGc6W9hqNpURZYqqBeLvdEDkKNUnHlYdA4C938wTn1DI3XamE-2FHVs5dolvXKj6piyN1PwIsrbNT7RIN6S1F5pTUb0c3wWBTwktEiLA7Lwkap72KuINBVRqLrrt6DrtmlDa6K2Dk8ONWql0E6Qra-2FaAFtNUagm0PevgK6WHeLiv9w-3D-3D)

> - Na czym polega ta aplikacja? Do czego służy?

  - Aplikacja *Scouts panel* służy do zbierania informacji na temat piłkarzy oraz ich edycja, zarówno w języku polskim, jak i angielskim.


> - Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a? (Nie bój się wyrażać opinię!)

Funkcjonalności:
- logowanie do panelu
- przypomnienie hasła do logowania
- zmiana języka polski/angielski
- 
-

  
  - W podstronie *Gracze* umieściłabym przycisk dodawania nowego gracza.

- W podstronie *Gracze* przy wymienionych graczach umieściłabym akcje - np. symbol *ołówka* sugerujący edycję danej pozycji.

w *dodaj język* lista rozwijana

*Łączy nas piłka*, *90 minut* - nie wiadomo co to znaczy, jakimi danymi uzupełnić nazwane w ten sposób pola.

W formularzu *Edycja raportu* w polu *Wstęp* wprowadziłabym ograniczenie do jednego akapitu.

  
> - Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?

*rozpocznij mecz* nie ma żadnego wyjaśnienia w jaki sposób uzupełnić informacje w tym temacie.


  
> - Czy aplikacja jest intuicyjna? (Intuicyjna, czyli np. nie masz problemu ze zrozumieniem, co należy kliknąć, żeby wejść do formularza dodawania nowego zawodnika piłki nożnej do systemu).

W formularzu *Dodawania gracza* województwo nie jest obowiązkowym polem do uzupełnienia, a w momencie dodawania raportu na podstawie meczu pojawia się komunikat, że pole "województwo" danego gracza jest wymagane.
  
> - Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem? Zapisz swoje przemyślenia w pliku. 

- Brak możliwości założenia konta do panelu

- Przechodząc ze *Strony głównej* do podstrony *Gracze* przechodzimy do dowolnego gracza, klikając w dowolną informację o danym graczu, w menu bocznym (po lewej stronie), Wybierając w *Raportach* przycisk *Dodaj raport* wyświetla się podstrona *Mecze* zamiast formularza dodawania raportu. Dodanie raportu możliwe jest tylko w podstronie *Mecze*, gdy jest dodany przynajmniej jeden mecz

dodawanie gracza możliwe tylko z *Linków pomocniczych* znajdujących się na *Stronie głównej*.

**Dodawanie / Edycja gracza**

- Wpisując do formularza *Edycja gracza* dane liczbowe w polach *wzrost* i *waga*, system zezwala na wyświetlanie liczb ujemnych oraz nierealnych (np. 2 cm wzrostu oraz 2000 kg masy ciała).

- W formularzu *Edycji gracza* przycisk *Clear* powoduje cofnięcie wprowadzonych zmian, a nie usunięcie danych ze wszystkich pól, jakby sugerowało to słowo.

w pola obowiązkowe można wpisać spację i formularz jest akceptowany

w polu *Imię* oraz *Nazwisko* można wpisać dowolne znaki

data urodzenia nie ma limitu, można wybrać datę poniżej 1900 r. i powyżej 2023 r.

numer telefonu - zezwala na wprowadzenie dowolnych znaków zamiast cyfr

e-mail - zezwala wprowadzać dowolne znaki, jednocześnie nie informując w czym jest błąd (wymagany znak *@*)

link z YouTube - dowolne znaki, bez sprawdzenia czy jest to url

*Dodaj język* - pozwala wprowadzić dowolne znaki

brak możliwości usunięcia dodanego gracza

- W formularzu *Edycja gracza* oraz *Edycja meczu* w języku polskim przyciski *submit* oraz *clear* powinny być przetłumaczone na język polski.

w angielskiej wersji formularza *Edycja gracza* województwa w liście rozwijanej nie są prawidłowo przetłumaczone.


**Dodawanie / Edycja meczu**

*Web match* oraz *General* są nieprzetłumaczone w polskiej wersji językowej formularza *Edycja meczu*

jeśli nie zaznaczy się rodzaju meczu to zaznacza się druga z kolei opcja *mecz wyjazdowy*

*czas gry* nie ma podanej jednostki (min) oraz może być wypełniony wartością *0*

*Rozpocznij mecz* - można dodawać duże ilości połowy meczu (gdzie w domyśle są tylko dwie).


**Edycja raportu**

W formularzu edycji raportu podpowwiedź do pola *Inteligencja boiskowa* w pierwszym zdaniu jest użyty podwójnie ukośnik, a kilka słów dalej zabrakło jednego z nich (rozdzielenie słów *piłki* od *Ocena*)

W formularzu edycji raportu w podpowiedzi do pola *Mentalność* w dwóch ostatnich zdaniach brakuje znaków interpunkcyjnych (kolejno: kropki oraz znaku zapytania).

W formularzu edycji raportu w podpowiedzi do pola "Recenzja" pierwsze zdanie ("Wybieramy 1 spośród poniższych punktów") jedynka powinna być zapisana słownie aby nie wprowadzać w błąd przy ocenie w skali 1-5. Dodatkowo formularz pozwala zaznaczyć połowę "gwiazdki".

Formularz *Edycja raportu* pozwala zapisywać niewypełnione wszystkie pola.

W formularzu *Edycja raportu* nieprawidłowo działa opcja wypunktowania listy - w przypadku próby dodania kolejnej pozycji do stworzonej listy, nie pojawia się przy niej kolejny symbol - kropka lub cyfra w przypadku listy numerowanej.

czasem Zaznaczając jedno z kilku słów i wybierając aby było zapisane kursywą, przechyla się również słowo znajdujące się w tej samej linijce przed oraz po wybranym słowie.

brak instrukcji oraz tytułu podstrony "rozpocznij mecz"
zegar odliczający czas - mecz trwa zwykle ok. 90 min
przy dużej ilości akcji pole boiska jest nieczytelne


przechodząc z wypełnianego formularza użytkownik nie zostaje zapytany o to czy na pewno chce porzucić wprowadzane informacje

### Subtask 5: Jira (zadanie dodatkowe)
