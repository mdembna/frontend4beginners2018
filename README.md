# Front End 4 Beginners

![baner kursu](assets/baner.png)

# Plan zajęć

![plan zajec](assets/plan_zajec.jpg)

# Materiały z zajęć
Tutaj dzień po zajęciach znajdziecie prezentacje oraz treść zadań domowych.

1. Wprowadzenie do HTML ([Prezentacja](assets/Wyklad01_Wprowadzenie_do_HTML.pdf))
    - Praca domowa: Na bazie wizualizacji zaproponuj strukturę strony używając znaczników poznanych na wykładzie.
Napisany kod należy zapisać jako plik z rozszerzeniem .html (np. index.html) i umieścić na GitHubie.
Staraj się projektować strukturę w taki sposób, żeby czytana od góry do dołu miała logiczny sens.
    - Wyniki pracy domowej ([link](https://docs.google.com/spreadsheets/d/1BMQbbnORhr-1lBsGiyHfg-J6rZVIQ0LQgIpcYjc8AOA/edit?usp=sharing))
    - Przykładowe rozwiązanie ([link](https://github.com/daftcode/frontend4beginners2018/blob/master/przykladowe-rozwiazania/zadanie01/index.html))
    - Omówienie błędów z pracy domowej ([link](https://github.com/daftcode/frontend4beginners2018/blob/master/omowienia-prac-domowych/Zadanie01_HTML_b%C5%82%C4%99dy.pdf))
    
2. Podstawy CSS ([Prezentacja](https://github.com/daftcode/frontend4beginners2018/blob/master/assets/Wyklad02_Podstawy_CSS.pdf))
    - Praca domowa: Na bazie poprzedniej pracy przygotuj w CSS'ie layout strony:
      - Menu z logiem przyklejone do lewego górnego rogu a menu social media do lewego dolnego rogu (powinny być w tym samym miejscu ekranu niezależnie od przewijania strony, patrz: animacja wyżej)
      - Każda główna sekcja strony (Home, About, Concerts, itd...) powinna mieć wysokość równą pełnej wysokości okna przeglądarki (lub wyższą, jeśli treść sekcji zajmuje więcej miejsca).
      - Zaproponuj sposób ułożenia sekcji głównych, żeby dobrze się prezentowały na różnych szerokościach ekranu (można to testować rozszerzając i zwężając okno przeglądarki)
      - W tym etapie nie ma znaczenia kolorystyka strony i tekstów, ale można sobie pokolorować sekcje w celach pomocniczych
      - Jeżeli struktura HTMLowa z poprzedniego zadania utrudnia/uniemożliwia osiągnięcie pożądanego efektu, dokonaj stosownych modyfikacji starając się trzymać zasad omówionych na poprzednim wykładzie
    - Wyniki pracy domowej ([link](https://docs.google.com/spreadsheets/d/1BMQbbnORhr-1lBsGiyHfg-J6rZVIQ0LQgIpcYjc8AOA/edit#gid=1779684322))
    - Przykładowe rozwiązanie ([link](https://github.com/daftcode/frontend4beginners2018/tree/master/przykladowe-rozwiazania/zadanie02))
    - Omówienie błędów z pracy domowej ([link](https://github.com/daftcode/frontend4beginners2018/blob/master/omowienia-prac-domowych/Zadanie02_CSS_b%C5%82%C4%99dy.pdf))
    
3. Let's CSS like a pro! ([Prezentacja](https://github.com/daftcode/frontend4beginners2018/blob/master/assets/Wyklad03_Lets_CSS_like_a_pro.pdf))
    - Praca domowa: Bazując na wizualizacji (https://zpl.io/scene/Vx1dY8W) zakoduj warstwę wizualną strony:
        - Zbuduj finalną strukturę wszystkich sekcji strony
            * postaraj się dobrać adekwatną technikę do ułożenia danej sekcji (flexbox, position relative/absolue, inline-block)
        - Zdefiniuj wygląd tekstów na stronie, zwracając uwagę na:
            * Kolor
            * Rozmiar tekstu
            * Pogrubienie lub brak pogrubienia
            * Letter spacing
            * Line-height
            * Opacity
        - Spraw, aby tło strony pozostawało w tym samym miejscu, niezależnie od paska przewijania
            * Do osiągnięcia tego efektu zapoznaj się z właściwością "background-attachment"
            * Pożądany efekt możesz zobaczy na animacji w materiałach do pracy domowej (https://github.com/daftcode/frontend4beginners2018/blob/master/README.md#materia%C5%82y-do-projektu)
        - Ostyluj elementy formularza:
            * Przyciski (na razie tylko stan "default" z wizualizacji, pozostałe stany obsłużymy na kolejnych zajęciach)
            * Pola tekstowe
            * Labelki
        - Zadbaj o odpowiednie marginesy i paddingi we wszystkich sekcjach strony (odległości od krawędzi ekranu, odległości nagłówków od treści, itp)
    - Wyniki pracy domowej ([link](https://docs.google.com/spreadsheets/d/1BMQbbnORhr-1lBsGiyHfg-J6rZVIQ0LQgIpcYjc8AOA/edit#gid=1126655829))
    - Przykładowe rozwiązanie ([link](https://github.com/daftcode/frontend4beginners2018/tree/master/przykladowe-rozwiazania/zadanie03))
    - Omówienie błędów z pracy domowej ([link](https://github.com/daftcode/frontend4beginners2018/blob/master/omowienia-prac-domowych/Zadanie03_CSSvol2_b%C5%82%C4%99dy.pdf))

4. Responsive Web Design ([Prezentacja](https://github.com/daftcode/frontend4beginners2018/blob/master/assets/Wyklad04_Responsive_web_design.pdf))
    - Praca domowa: Zmodyfikuj swój projekt, aby zachowywał się w sposób responsywny. W tym celu:
        - Umieść w znaczniku `<head>` strony odpowiedni meta tag, żeby lepiej wspierać wersję mobilną strony
        - Przetestuj zachowanie swojej strony:
            * zmieniając rozmiary okna przeglądarki (głównie szerokość), obserwuj, czy elementy strony nie zachowują się w sposób niepożądany (nie rozjeżdżają się, nie nachodzą na siebie, tekst nie łamie się w brzydki sposób)
            * dodatkowo możesz uruchomić symulator urządzenia mobilnego w Chrome Dev Tools (instrukcja: https://developers.google.com/web/tools/chrome-devtools/device-mode/)
        - Postaraj się poprawić jak najwięcej niepoprawnie zachowujących się elementów używając dotychczasowo poznanych technik:
            * elastycznych kontenerów
            * zawijania tekstu
            * pozycjonowania
            * flex-wrap
        - Jeśli mimo powyższych zabiegów niektóre sekcje nie będą się dobrze prezentować (np. nie zmieszczą się na szerokość ekranu), zaproponuj przedziały Media Query, które pozwolą obsłużyć te sytuacje
            * przykładowe trzy przedziały: dla smartfona, dla małego laptopa, dla dużego monitora Full HD
            * na tym etapie możesz śmiało dokonywać zmian w projekcie graficznym w celu uzyskania estetycznego i użytecznego wyglądu strony
        - Uwaga - W przypadku wideo z YouTube uzyskanie idealnego wyglądu może wymagać zaawansowanych technik, dlatego w ramach niezbędnego minimum spraw, aby wideo mieściło się na szerokości strony.
    - Wyniki pracy domowej ([link](https://docs.google.com/spreadsheets/d/1BMQbbnORhr-1lBsGiyHfg-J6rZVIQ0LQgIpcYjc8AOA/edit#gid=425981761))
    - Przykładowe rozwiązanie ([link](https://github.com/daftcode/frontend4beginners2018/tree/master/przykladowe-rozwiazania/zadanie04))

5. Be aWWWesome ([Prezentacja](https://github.com/daftcode/frontend4beginners2018/blob/master/assets/Wyklad05_Be_aWWWesome.pdf))
    - Praca domowa: Dodaj do strony efekty wizualne:
        - Po najechaniu myszką na członków zespołu ich wizerunki powinny zostać podświetlone a opisy pod nimi stać się widoczne
        - Podświetl przyciski (hover, focus, active) oraz linki dla różnych stanów (hover, focus)
        - Po najechaniu myszką na zdjęcia z galerii powinny się powiększyć
        - Zmiany wyglądu z powyższych punktów powinny zachodzić w sposób płynny
        - Pożądany efekt można zaobserwować w animacji z materiałów do projektu
    - Wyniki pracy domowej ([link](https://docs.google.com/spreadsheets/d/1BMQbbnORhr-1lBsGiyHfg-J6rZVIQ0LQgIpcYjc8AOA/edit#gid=1520718741))
    - Przykładowe rozwiązanie ([link](https://github.com/daftcode/frontend4beginners2018/tree/master/przykladowe-rozwiazania/zadanie05))

6. Wyniki pracy domowej - zestawienie ogólne ([link](https://docs.google.com/spreadsheets/d/1BMQbbnORhr-1lBsGiyHfg-J6rZVIQ0LQgIpcYjc8AOA/edit#gid=924665370))

# Praca domowa - projekt strony internetowej

## Materiały do projektu
- Wizualizacja na platformie Zeplin: https://zpl.io/scene/Vx1dY8W
- Zdjęcia i grafiki użyte w wizualizacji: [Link](assets/6BM_zdjecia.zip)
- Teledysk do umieszczenia na stronie https://youtu.be/AstRXh-vKNI (lub własny, jeśli chcecie)
- Animacja prezentująca efekt końcowy pracy domowej po wszystkich zajęciach

![animacja](assets/video.gif)

# Informacje organizacyjne

## Komunikacja
Zajęcia są dla Was. Chcemy abyście wyciągneli z nich jak najwięcej. Dlatego przygotowaliśmy dla was dwa kanały komunikacji z nami. Piszcie jeśli macie pytania w sprawie prac domowych oraz wymieniajcie się doświadczeniami na GitHub Issues.
- Email: frontend@daftacademy.pl
- GitHub issues: https://github.com/daftcode/frontend4beginners2018/issues

## Obecności na zajęciach
Jesteśmy firmą technologiczną, taże pozbywamy się papieru i zaznaczmy obecność na zajęciach przez internet.
- Podczas zajęć logujemy się na https://daftacademy.pl/
- W prawym górnym roku klikamy w swoje Imię i Nazwisko
- Wybieramy opcję "Obecność"
- Przepisujemy kod z ekranu projektora

## Edytor kodu

Jeśli nie masz swojego ulubionego to polecamy:

https://code.visualstudio.com/

## Prace domowe
- Termin oddawania prac domowych - niedziela, 23:59 po danych zajęciach
- W celu oddania pracy wypełniamy otrzymany mailowo formularz Google Forms, w którym podajemy swoje dane i link do repozytorium z wykonaną pracą domową
- Kryteria oceny
    ~~~~
    - Punkty bazowe za poprawne wykonanie zadania (maksymalna liczba punktów będzie indywidualna dla każdej pracy domowej)
    - Punkty bonusowe za wysoką jakość kodu (max. 1pkt za pracę domową)
    - Punkty bonusowe za aktywność, przyznawane na koniec kursu (np. udział w dyskusjach i pomoc innym na GitHubie)
    ~~~~

### Wyróżnienie dla najbardziej zaangażowanych osób (certyfikaty ukończenia kursu + gift packi):
- Obecność na minimum 4 z 6 zajęć
- Minimum 70% punktów bazowych za prace domowe


# Umieszczanie pracy domowej na GitHubie

- Zakładamy konto na GitHub.
- Klikamy w prawym górnym rogu `+`
- Wybieramy opcję `New repository`
- Wpisujemy nazwę `daftacademy_frontend4begginers`
- Zaznaczamy pole `Initialize this repository with a README`
- Klikamy `Create repository`

Od teraz wchodząc na nasze repozytorium projektu możemy metodą drag&drop przenosić pliki i wgrywać je do naszego repo.

Każda aktualizacja projektu to tzw. `commit` czyli opis zmian w porównaniu do poprzedniej wersji projektu.

Gotową pracę domową wysyłacie do nas w formularzu Google Forms otrzymanym w mailu po zajęciach.

# Pomoc przy pracach domowych, pytania dotyczące treści zajęć
Zachęcamy do zadawania pytań przez [Issues](https://github.com/daftcode/frontend4beginners2018/issues) tego projektu. Przeglądajcie również pytania innych uczestników, może potraficie na nie odpowiedzieć! :D
      
