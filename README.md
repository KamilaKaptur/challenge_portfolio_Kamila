# TASK 1
## SUBTASK 1
10 punktów
## SUBTASK 3
Cześć! Nazwyam się Kamila i zdecydowałam się wziąć udział w projekcie, ponieważ kilka miesięcy temu postanowiłam zostać testerem oprogramowania. Pomyślałam "jak nie teraz to kiedy?" i tak od kilku miesięcy testowanie to coś co wypełnia moje dni. Chcę być w tym najlepsza dlatego postanowiłam wybrać Wasz projekt dzięki, któremu z praktycznej strony poznam tajniki testowania. 

Moim celem jest sprawdzenie swojej dotychczasowej wiedzy na temat testowania, nauka od strony praktycznej oraz oczywiście walka o staż :) 

**Kamcia**

## SUBTASK 4
**Na czym polega ta aplikacja? Do czego służy?**
Aplikacja polega na zarządzaniu graczami i meczami. Służy do tworzenia profili graczy, tworzenia raportów. Dzięki niej możemy przeglądać wszelkie wskaźniki danych zawodników. Przydatna aplikacja dla tzw. skautów czyli łowców taletów piłki nożnej. 

**Jakie funkcjonalności znajdują się w aplikacji? Do czego służą. Czy są intuicyjne, czy może byś coś zmienił_a?**

W aplikacji znajdują się takie funkcjonalności jak: 
* Dodaj gracza

Plus za to, że link do formularza znajduje się na głównej stronie. Sam formularz prosty w obsłudze.
* Edycja gracza

Brak przycisku edycji gracza sprawia, że przeciętny użytkownik może nie zauważyć tej funkcji. Bardzo nieintuicyjne rozwiązanie, zwłaszcza, że przez tą funkcję docieramy do innych funkcjonalności aplikacji.
* Dodaj mecz

Funkcjonalność ukryta, może sprawiać problem aby użytkownik ją odnalazł. Możemy dodać mecz dopiero po wybraniu zawodnika i kliknięciu zakładki "mecze".
* Edytuj mecz

Edycja meczu jest możliwa po kliknięciu na danego zawodnika, następnie wybraniu zakładki "mecze". Wtedy w opcjach pojawia się "edytuj". Nieintuicyjne rozwiązanie. Powinno być ono bardziej dostępne i widoczne. 
* Dodaj raport

Tak samo jak przy poprzedniej funkcjonalności w akcjach pojawia się "dodaj raport" lub w zakładce raporty. Również mało widoczna funkcja. 
* Edytuj raport 

Aby wejść w edycje raportu należy kliknąć na zawodnika, później pokaże się nam funkcjonalność "raporty" nastepnie w zakładce akcje mamy funkcje edycji raportu. To dość długa ścieżka jak na tak podstawową funkcje. Powinna być znacznie uproszczona i bardziej dostępna dla użytkownika. W edytorze raportu możemy łatwo zedytować tekst pomimo, że strona nie jest responywna i może sprawiać trudności przy użytkowaniu. 
* Rozpocznij mecz

Podobnie jak poprzednie funkcjonalności dość "ukryta" funkcja. Na pierwszy rzut oka ciężko zrozumieć co jest jej celem oraz jak osługiwać tą funkcjonalność. Proponowałabym legende oraz krótki opis.

* Pozostałe: Pobieranie pliku CSV, drukowanie, zmiana języka na angielski, odznaczanie wyświetlania poszczególnych kolumn, opcja filtrowania wyników. 

**Oceń interfejs aplikacji (wygląd) – czy Ci się podoba, czy nie?**

Interfejs w mojej opini jest zbyt ubogi. Lubię proste rozwiązania jednak prostota w tym przypadku wiąże się z nieprzyjemnym dla oka interfejsem. Moim zdaniem warto byłoby dodać na stronę trochę elementów graficznych i więcej kolorów.

**Czy aplikacja jest intuicyjna?**

Aplikacja nie jest intuicyjna. Aby znaleźć niektóre funkcjonalności trzeba się naszukać lub domyślać. Przeciętny użytkownik mógłby mieć problemy ze znalezieniem niektórych z funkcji. 

**Czy zauważasz jakieś błędy? Albo coś wydaje Ci się błędem?**

Wykryte przeze mnie błędy:

* Brak możliwości usunięcia stworzonego przez nas gracza

* Możliwość wpisania liczb ujemnych w profilu gracza np. w polu waga czy wzrost

* W profilu gracza w polu data urodzenia możliwość wybrania daty, która jeszcze nie nadeszła

* Możliwość wpisania liczb ujemnych w edycji meczu w polu zdobyte gole, stracone pole

* Niespójności w UI. Brak przycisku infomującego o możliwości edycji gracza (tylko podświetlenie), natomiast w "meczach" i "raportach" odpowiedni przycisk do akcji

* W wesji polskiej strony niektóre przyciski takie jak "save", "clear", "submit" wyświetlają się po angielsku

* Brak walidacji przy wpisaniu niepoprawnego adresu e-mail np. abc

* W edycji gracza i edycji meczu nie działający przycisk "clear"

* W funkcji "Show Columns" możliwość odznaczenia wszystkich kolumn



