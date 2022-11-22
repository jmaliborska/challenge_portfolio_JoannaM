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

**TASK 4** 
=
**Subtask1**
----
link do zadań: https://drive.google.com/drive/folders/1ahXgWlGJ6e--fYCmc10Mb4XNGzl0efCk?usp=share_link
#####
**Subtask3**
----
1. Do czego służy aplikacja https://focusly.co/ ? Jaki jest cel tej aplikacji? \
Aplikacja służy do:
- samorozwoju, edukacji rozwijaniu zagadnień z psychologii;
- zorientowania na złapanie równowagi  w życiu,  uwolnienie energii „mind-flow”; 
- medytacji;
- znalezieniu chwili dla siebie w otaczającym nas świecie (pędu życia, prze-bodźcowaniu);
- nauki oddychania i wyciszenia;
- skupienie się na sobie „wewnętrznemu ja”.

2. Kto ma być użytkownikiem końcowym aplikacji? \
Osoby, które pragną się rozwijać w wielu aspektach życiowych i duchowych. Pomocna w walce z różnymi jednostkami chorobowymi np. stany lękowe, nerwice, bezsenność. Dzięki nauce wyciszenia oraz oddychania, życie może okazać się dla nich łatwiejsze w stresujących momentach. Użytkownicy który chcą skupić się również na psychologii, samoakceptacji i rozwoju.

3. Czy według Ciebie aplikacja jest user friendly? \
W ogóle nie jest przyjazna. Panuje chaos, który może prowadzić do zakłopotania oraz frustracji a aplikacja ma docelowo pomagać w rozładowaniu stresu. Ze względu na poświęcony czas i cierpliwość podczas testów eksploracyjnych doszłam do wniosku jak poruszać się po aplikacji. Jednak nawet nawigacyjny klawisz (wstecz)nie leży w obrębie kciuka a jest położony u góry w aplikacji

4. Jak byś usprawnił aplikację? 
	
- Klawisz back w obrębie kciuka a nie u góry aplikacji- aktualnie utrudnia użytkownikowi poruszanie się po aplikacji;
- Dodanie w panelu głównym ulubionych(serduszko) sekcji: utworów, muzyki, wykładów- szybki dostęp;
- W głównym menu można dodawać tylko po jednej opcji np. „kurs wprowadzający”, „cel”, „Dla Ciebie”, „Wyzwania”. Jest to dość uciążliwe, dlaczego użytkownik nie może mieć większej ilości sekcji – testowałam subskrypcję free;
- Wprowadzenie motywacyjnych przekazów dnia, hasła, motta;
- Wprowadzenie astralnych faz księżyca, układów planet itp. – częste odwołania w medytacji;
- Wdzięczność- częste odwołania w medytacji, aby użytkownik po zadanym pytaniu mógł zastanowić się nad swoim życiem, za co jest wdzięczny itp.;
- Powiadomienia push up gdy użytkownik nie zaglądał do aplikacji przez określony czas np. 2 dni;
- Sekcja „Twórcy”: ujednolicić format zdjęć np. wszyscy posiadają identyczne tło, zdjęcie profilowe. Aktualnie panuje chaos, brak spójności. 
„Papier wszystko przyjmie”idąc tą ideą by uwiarygodnić kompetencje twórców odnośniki do profili FB, Linkedin. By użytkownik mógł faktycznie zweryfikować profil danego twórcy.
Kolejny aspekt na jaki należy zwrócić uwagę to wyrównanie tekstu od lewej do prawej strony każdego twórcy, aby wszystko wyglądało schludnie. Przesunięcie pojedynczych liter na końcu wiersza np. „i”, „z” do kolejnego wiersza.
Rozwinięcie biografii o danym twórcy. Aktualnie słowo”Więcej” a po rozwinięciu biografii słowo „ Ukryj” jest uwydatnione większą czcionką. Wg mnie lepszy byłby ten sam rozmiar czcionki co cały tekst lub mniejszy. Jednak by wyróżnić słowo zaznaczyć pogrubieniem/podkreślaniem lub dodaniem słowa w kolorze -aby rzucał się w oczy; 
- Sekcja Oddychaj opis konfiguracji aktualnie nieświadomy użytkownik nie wie czym różni się np. poziom trudności: podstawowy, średnio-zaawansowany i zaawansowany. Jak użytkownik może określić swój poziom trudności?;
- Ujednolicenie panelu odsłuchiwania nagrań. W sekcji „odkrywaj” można przejść do następnego utworu, zaś w sekcji ”muzyka”taka opcja jest niedostępna.  Kolejną kwestią do rozważenia zmiany jest przesunięcie czasowe materiału. Aktualnie dostępna jest opcja przesuwania materiału o 15sekund do przodu/tyłu. Powinny być kolejne jednostki czasowe np. 30sekund, 1 minuta, 3minuty. Użytkownik wybiera opcję czasową jaka mu odpowiada. Wprowadzenie opcji zakładki aby wrócić do nagrania w danym momencie gdy np. użytkownik w danym momencie wychodzi z osłuchanego utworu a ma ochotę wrócić do niego w innym terminie.



5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej? \
To zależy od aplikacji. Trudniejszy dostęp do logów, devtoolsów są na aplikacjach natywnych. Na każdym urządzeniu mobilnym aplikacja może zachować się inaczej.
