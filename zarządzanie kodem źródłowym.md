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

-   - Na głównej stronie Git-a znajduje się rozbudowany opis działania programu
    w wielu językach w tym również polskim



-   Git nawet do tworzenia prostych projektów wymaga znajomości wielu komend

-   - Istnieje wiele darmowych kompatybilnych z Git-em wersji graficznych tego
    programu (Git Extensions,SOurce Tree)

-   - Zaznajomienie się z obsługą tych programów zwiększy nieco czas
    przeznaczony na zapoznanie ze środowiskiem Git-a



-   W internecie nie ma instrukcji, tutoriali dotyczących obsługi Git Extensions
    napisanych po polsku

-   - Posiłkowanie się angielską wersją obsługi programu zwiększa czas
    przeznaczony na projekt



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

-   - Stosuję kompatybilny z Git-em program Kadiff3, będący narzędziem pomocnym
    przy samodzielnym mergowaniu



-   Przy merge-owaniu dochodzi od usunięcia pliku źródłowego z  wcześniejszego
    commitu

-   Problem nie narusza pracy projektu- plik tekstowy pozostaje bez zmian



-   Podczas próby zrzucenia projektu na portal github.com występuje błąd

-   - Problem rozwiązuje zmiana nazwy autora bez wpisywania polskich znaków



-   Przy próbie umieszczenia projektu na serwerze hostingowym GitHub zostaje
    umieszczona jedynie jedna gałąź(Master)

-   - niezbędne jest przy "push-owaniu" wyodrębnienie każdej z gałęzi



-   Przy próbie mergowania do gałęzi "master" dochodzi do usuwania całego tekstu
    i pliku źródłowego

-   - problem znika przy zastosowaniu P4merge jako narzędzia do mergowania



-   Tagi umieszczane za pomocą graficznej wersji nie są widoczne w wersji
    umieszczonej na GitHub

-   - widoczność tagów na stronie hostingowej jest możliwe tylko przez
    umieszczeniu ich za pomocą GitGui lub Git Bash



-   P4merge dokonuje jedynie porównania ze sobą dwóch wersji projektu

-   - niezbędna jest zmiana w ustawieniach poprzez ustawienie P4merge-a nie
    tylko jako "External Diff Tool" ale również jako "Merge Tool" , SourceTree
    domyślnie nie ustawia żadnego programu do ręcznego merge-owania



-   Graficzna wersja Git-a - SourceTree dostępna jest w wersji trial, z
    możliwością korzystania bez licenicji przez okres dwóch tygodni

-   - Zarejstrowanie programu jest darmowe i trwa jedynie kilka minut



-   





Wnioski:


