**TASK 1** 
=
**Subtask 1**
----

5\10pkt :slightly_frowning_face:
######
**Subtask 3**
----
Cześć Mam na imię Joanna. Po prawie trzynastu latach działania w branży ubezpieczeń jako agent ubezpieczeniowy postanowiłam przebranżowić się. Myślę, iż dzięki udziałowi w wyzwaniu Dare IT zbuduję ciekawe porfolio, nawiążę kontakt z menetorkami a także osobami, które są w podobnej sytuacji życiowej. Dodatkowo uzyskam praktyczną wiedzę(esencję), która pozwoli mi wyróżnić się na tle innych kandydatów na stanowisko testera manualnego. Ogromnym wyróżnieniem byłby staż z firmy parnerskiej z którą współpracuje Dare IT.\
Jestem osobą kreatywną, sumienną, cierpliwą, ciekawą świata, lubię zdobywać nową wiedzę. Należę do osób komunikatywnych, bardzo lubię pracować w zespole. Nie stważam problemów. Uważam, iż rozmowa i wzajemny dialog z osobami z zespołu jest kluczem w dobrych relacjach.\
W wolnych chwilach lubię aktywnie spędzać czas na treningach siłowych a także uprawiąjąc akrobatykę powietrzną. Wieloletnie treningi nauczły mnie pokory oraz uzmysłowiły fakt, iż cierpliwość i wytrwałość jest kluczem do osiągnięcia sukcesu. W ubiegłym roku zainteresowałam się tematyką haftu ręcznego. Haftowanie relaksuje mnie po intesywnym dnia a także pozwala wyzwolić pokłady kreatywności. Ponadto w kręgu moich zainteresowań znajduje się tematyka zdrowego odyżywiania oraz behawioryzm zwierząt.
######
**Subtask4**
----
Aplikacja https://scouts-test.futbolkolektyw.pl/pl \
* testowana na przeglądarce Chrome Wersja 106.0.5249.119 (Oficjalna wersja) (64-bitowa) 
* testowana z  konta user01@getnada.com pass: Test-1234 oraz konta user09@getnada.com pass: Test-1234

1. Na czym polega ta aplikacja? Do czego służy?\
Aplikacja do zarządzania graczami(mierzeniem ich postępów z gry, analizą sytuacji), Analiza przebiegu meczu i do tworzenia raportów z rozgrywek. Analiza drużyny oraz drużyn przeciwnych.

2. Jakie funkcjonalności znajdują się w aplikacji? 
* dodawanie graczy, meczy oraz raportów,
* opis przebiegu meczu,
* raporty zawodników ,
* analiza meczu,
* wysyłanie raportu do pliku csv,
* filtrowanie użykowników,
* drukowanie raportu,
* edycja parametrów użytkownika

3. Oceń interfejs aplikacji.\
Bardzo prosty- za prosty jak na obecne czasy, długi czas oczekiwania-6sekund po dodaniu nowego gracza lub zapisaniu zmian. 
4. Czy aplikacja jest intuicyjna? \
Tak. Jednak brakuje samouczka "Step By Step" dla nowego użytkownika
5. Czy zauważasz jakieś błędy?
* Główny panel. Gdy docelowo wybrany jest język polski to wyświetla się napis w języku angielskim "Scouts Panel"(zarwóno na niebieskiej belce u góry strony, jak i po prawej stronie, obok menu, pod logo "Futbol Kolektyw,Platfroma Skautingowa" \
* Pod logo "Scouts Panel" Dev team contact - po klikniećiu w klink zamiast pokazać możliwość kontaktu z zespołem developerskim użytkownik jest przekierowywany na stronę slacka do której nie ma dostępu
* Formularz dodawania gracza: Tylko 4 pola obowiązkowe. wystrczy wpisać 1 literę imienia oraz nazwiska a także podać cyfrę w polu "główna pozycja" a także datę urodzania by dodać nowego gracza
* Formularz dodawania gracza: można dodać gracza, który się jeszcze nie urodził (podanie przyszłej daty)oraz gracza któy ma np. 200lat
* Formularz dodawania gracza: można dodać gracza, który ma ujemną wagę oraz wagę powyżej normy np. 200kg w zwyż
* Formularz dodawania gracza: można dodać gracza, który ma ujemny wzrost oraz wzrost powyżej normy np. 260cm.
* Formularz dodawania gracza: można podać teleefon z jedną cyfrą oraz z większą ilością cyfr niż może mieć numer
* Formularz dodawania gracza: nie trzeba podawać adresu e-mail zawodnika oraz można podać adres e-mail 
* Formularz dodawania gracza: pole Link do YouTube można wpisać cokolwiek-system przyjmie wartrość
* Formularz dodawania gracza: pole profil FB, można wpisać cokolwiek -sytstem przyjmie wartość
* Formularz dodawania gracza: pozycja główna, można wpisać cokolwiek - system przyjmie wartość, lepsza lista rozwijalna do wyboru
* Formularz dodawania gracza: pozycja alternatywna, można wpisać cokolwiek - system przyjmie wartość, lepszaista rozwijalna do wyboru
* Formularz dodawania gracza: pole jezyk, można wpisać cokolwiek - system przyjmie wartość, lepsza lista rozwijalna z językami do wyboru
* Menu Gracze, Filtr wiek: można wpisać ujemną wartość i filtr zadziałą (poda błędne dane)
* Brak zakładki mecze oraz raporty w panelu głównym (lista po lewej stronie)
* Mecze, Akcja dodaj raport: raport meczowy. Gdy chcemy opisać zdarzenie z meczu i używamy listy numerycznej to możemy tylko użyć cyfry 1. Kolejne nie wczytają się
* Mecze, Akcja dodaj raport: raport meczowy. Niebieski Guzik Save po lewej stronie, scrollując stronę w dół cały czas go widzimy. Guzik save powinien być widoczny w jednym miejscu a nie "płynąć z tekstem"
* Mecze, Akcja rozpocznij mecz: można wpisać nieskończenie wiele "połówek meczu" 
* Mecze, Akcja rozpocznij mecz: można wpisać nieskończoną ilość czasu
* Mecze, Akcja rozpocznij mecz: brak oznaczenia jednostki czasu sekunda, minuta, goodzina
* Mecze, Akcja rozpocznij mecz: brak pola dogrywka
* Mecze, Akcja rozpocznij mecz: brak możliwości ingerencji w graficzną prezentację boiska np. nie można przesynąć zawodnika na boisku, odznaczyć akcji
* Panel główny. Na środku pulpitu widoczny "link pomocniczy: dodaj gracza", zaś u góry strony opcje: ilość graczy, ilość meczy, ilość raportów, ilość akcji nie posiada linków przekierowujących na podstronę. 
* Panel główny. Na środku pilpitu widoczny link pomocniczy dodaj gracza. Ta opcja powinna być widoczna w menu po lewej stronie. A nie "wrzucona na środek strony"
* Mecze, Dodaj mecz lub edytyj mecz: można wpisać przyszłą datę meczu; można wpisać mecz z datą zamierzchłą np rok 1000
* Mecze, Dodaj mecz lub edytuj mecz: można wpisać nieskończenie wielką cyfrę straconych goli i wygranych goli np. 9999999988888888
* Mecze, Dodaj mecz lub edytuj mecz: czas gry, nie określono parametru czasu: sekunda, minuta, godzina
* Mecze, Dodaj mecz lub edytuj mecz: czas gry, można wpisać ujemną cyfrę np. -10


######
**TASK 2** 
=
link do zadań: https://drive.google.com/drive/folders/1owc2aPJm09I_pS6gKpjIfeo_iycB46p-?usp=sharing
