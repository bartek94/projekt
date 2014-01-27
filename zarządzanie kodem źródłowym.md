Zarządzanie kodem źródłowym



Bartosz Wiktorowski EE-DI-P6



Cel :

Stworzenie projektu z wykorzystaniem dowolnego programu do zarządzania kodem
źródłowym.

Opis:

W swojej pracy wykorzystam system kontroli wersji GIT będący wolnym
oprogramowaniem na licencji GNU General Public License. Efekty swojej pracy będę
zamieszczał  na hostingowym serwisie internetowym  https://github.com/ . Przy
pracy będę korzystał z graficznych wersji Git-a. Sam projekt będzie
przedstawiony jedynie w formie tekstu- nie będzie programem ze złożonym kodem w
języku programistycznym.



Terminarz:

-   zapoznanie z działaniem systemów kontroli wersji (np. pojęcia branch, merge
    itp.) (2h)

-   zapoznanie ze środowiskiem GIT (4h)

-   założenie konta na serwisie github.com, stworzenie repozytorium (0.5h)

-   tworzenie projektu (5h)

-   analiza i wnioski (1h)



Problemy:

-   Git nie posiada sam w sobie jakiejkolwiek pomocy tłumaczącej istotę programu
    oraz posługiwanie się nim

-   - na stronie git-scm.com znajduje się rozbudowany opis działania programu w
    wielu językach w tym również polskim



-   Git nawet do tworzenia prostych projektów wymaga znajomości wielu komend

-   - Istnieje wiele darmowych kompatybilnych z Git-em wersji graficznych tego
    programu (Git Extensions,Source Tree)

-   - Zaznajomienie się z obsługą tych programów zwiększy nieco czas
    przeznaczony na zapoznanie ze środowiskiem Git-a



-   W internecie nie ma instrukcji, tutoriali dotyczących obsługi Git Extensions
    napisanych po polsku

-   - Posiłkowanie się angielską wersją obsługi programu zwiększa czas
    przeznaczony na projekt



-   Programy Git-a (GitBash i GitGui) nie uruchamiają się

-   - Ponieważ starsze wersje Git-a nie są kompatybilne z niektórymi systemami
    Windows-a (np.XP) niezbędne jest pobranie najnowszej wersji Git-a



-   Przy próbie uruchomienia GitBash okno komend otwiera się na sekundę po czym
    znika

-   - by Git się uruchamiał potrzebne jest pobranie z internetu pliku
    msys-1.0.dll i umieszczenie go w katalogu Git-a w folderze "bin"



-   Przy próbie tworzenia projektu pojawia się problem brakującego na komputerze
    pliku libiconv2.dll

-   - poszukiwany plik znajduje się w katalogu Git-a w folderze "bin", z pewnych
    względów nie jest jednak wykrywalny przez program, skopiowanie go do folderu
    libexec/git-core usuwa błąd



-   Git nie zezwala na stworzenie nowego repozytorium na pulpicie

-   - Ponowne uruchomienie komputera rozwiązuje problem



-   Git nie obsługuje pewnych formatów, między innymi Windows-owego pakietu
    Microsoft Office

-   - Projekt wykonuję w tradycyjnym formacie txt



-   Plik w formacie notatnika(txt) pasiada bardzo ubogi system edycji tekstu

-   - Zmieniam format pliku na ".md" - języka znaczników Markdown , korzystając
    z programu Texts



-   Przy otwarciu pliku tekstowego okazuje się że Git nie czyta polskich znaków

-   - niezbędny jest update Git Extansions do najnowszej wersji



-   W momencie stworzenia nowej gałęzi(branch) usuwa się plik w
    repozytorium(folder jest pusty)

-   -ustawienia domyślne nie określają miejsca położenia pliku po zmianie
    gałęzi, problem rozwiązuje zmiana o opcjach katalogu "projekt" na domyślne
    repozytorium



-   Git nie jest w stanie poprawnie merge-ować plików w przypadku konfliktów

-   - Stosuję współpracujący z graficznymi wersjami Git-a program Kadiff3,
    będący narzędziem pomocnym przy samodzielnym merge-owaniu



-   Przy merge-owaniu dochodzi od usunięcia pliku źródłowego z  wcześniejszego
    commitu

-   - problem nie narusza pracy projektu- plik tekstowy pozostaje bez zmian

-   - zmiana programu na SourceTree, problem nie występuje



-   Podczas próby zrzucenia projektu na portal github.com występuje błąd nazwy
    autora

-   - Problem rozwiązuje zmiana nazwy autora bez wpisywania polskich znaków



-   Przy próbie umieszczenia projektu na serwerze hostingowym GitHub zostaje
    umieszczona jedynie jedna gałąź(Master)

-   - niezbędne jest przy "push-owaniu" wyodrębnienie każdej z gałęzi



-   Przy próbie mergowania do gałęzi "master" dochodzi do usuwania całego tekstu
    i pliku źródłowego

-   - problem znika przy zastosowaniu P4merge jako narzędzia do mergowania



-   P4merge dokonuje jedynie porównania ze sobą dwóch wersji projektu

-   - niezbędna jest zmiana w ustawieniach poprzez ustawienie P4merge-a nie
    tylko jako "External Diff Tool" ale również jako "Merge Tool" , SourceTree
    domyślnie nie ustawia żadnego programu do ręcznego merge-owania



-   Tagi umieszczane za pomocą graficznej wersji nie są widoczne w wersji
    umieszczonej na GitHub

-   - widoczność tagów na stronie hostingowej jest możliwe tylko przez
    umieszczeniu ich za pomocą komend w Git Bash



-   Graficzna wersja Git-a - SourceTree dostępna jest w wersji trial, z
    możliwością korzystania bez licenicji przez okres dwóch tygodni

-   - Zarejestrowanie programu jest darmowe i trwa jedynie kilka minut, program
    sam upomina się gdy okres próbny się kończy i przekierowywuje do rejestracji



-   Przy próbie zrzucenia projektu na serwer github.com zrzucana zostaje jedynie
    gałąź główna

-   - przy "push-u" niezbędne jest wyodrębnienie każdej z gałęzi



-   Push za pomocą SourceTree nie pokazuje na serwerze github.com tagów

-   - w opcjach należy zaznaczyć zrzucanie tagów na serwer



Wnioski:





Systemy kontroli wersji to pożyteczne narzędzia przy pracy zespołowej jaki i
również samodzielnej. Dają one możliwość stałego obserwowania efektów pracy jak
i również powrotu do dowolnego miejsca w czasie tworzenia projektu. Tworzenie
gałęzi pobocznych umożliwia równoczesne realizowanie paru pomysłów oraz łączenie
ich. W przypadku korzystania z Git-a dużym atutem jest to, iż posiada on wiele
graficznych wersji będących ułatwieniem w pracy - nie trzeba znać wielu komend,
aby łatwo posługiwać się programem. W czasie tworzenia projektu najwięcej
problemów sprawiło mi dostosowanie systemu kontroli wersji tak, aby działał bez
zarzutów.
