# Projektowanie i implementacja zaawansowanych aplikacji PHP

## Wprowadzenie

PHP to współczesny skryptowy język programowania dedykowany głównie dla rozwiązań webowych, którego pierwsza wersja została utworzona w 1994 roku przez Rasmus Lerdorfa. Początkowo był to zestaw prostych Common Gateway Interface (CGI), umożliwiających łączenie mechanizmów generowania stron HTML z kodem zaimplementowanym w języku C. Wraz z kolejnymi wydaniami języka (PHP 3 w roku 1998, PHP 4 w roku 1999, PHP 5 w roku 2004) był on wzbogacany o kolejne konstrukcje językowe, w tym koncepty programowania obiektowego. W 2015 roku wydana została wersja 7, w której całkowicie przeprojektowano mechanizmy runtime'u, zwiększając w ten sposób znacząco wydajność aplikacji opartych o język PHP.

Na przestrzeni lat język ten został obudowany szeregiem dodatkowych rozwiązań, wspomagających i upraszczających pracę developerów. Starsze aplikacje bardzo często korzystały więc z repozytoriów [PEAR](http://pear.php.net) oraz [PECL](https://pecl.php.net), obecnie sięga się bardzo często po rozwiązania m.in. typu [Composer](https://getcomposer.org) i powiązane z nim repozytorium [Packagist](https://packagist.org).

Swoją popularność język PHP zawdzięcza zarówno składni, upraszczającej proces poznawania języka, jak i bardzo rozbudowanemu ekosystemowi. Szacuje się, że język PHP (w różnych wersjach) jest wykorzystywany do obsługi ponad 83% znanych serwisów webowych.

Celem kursu jest nauka zarówno języka PHP jak i jego praktyczne wykorzystanie do implementacji złożonych aplikacji, w oparciu o aktualnie wykorzystywane narzędzia i rozwiązania (nowoczesne frameworki web, architektury aplikacji i systemu).


## Wymagania

Uczestnik zajęć powinien dysponować:

- podstawową wiedzą z zakresu programowania obiektowego
- podstawową znajomością relacyjnych baz danych (przydatne w drugiej części zajęć)


## Forma zajęć

Zajęcia odbywać się będą cyklicznie:

- wykład, sala 139, pt 10:15-12:00
- pracownia, sala 107, pt 08:15-10:00


## Pracownia

### Zasady zaliczenia przedmiotu
   
- W każdym tygodniu zajęć publikowane będzie zadanie, przeznaczone do samodzielnego zaprogramowania. Za każde poprawnie zaprogramowane zadanie i oddane w terminie można będzie dostać do 10 punktów.
- Zadania publikowane będą w tygodniu poprzedzającym termin ich realizacji. Zadania należy oddawać terminowo.
- Prezentacja wykonanych zadań odbywać się będzie na pracowni. Podczas prezentacji mogą zostać zadane dodatkowe pytania dotyczące rozwiązania.
- Ocena końcowa wynikać będzie z liczby zgromadzonych w trakcie zajęć punktów:
    - 50% na ocenę dostateczną
    - 90% na ocenę bardzo dobrą,
    - oceny pośrednie są ustalane liniowo względem określonych powyżej wartości

    
### UWAGA!

Terminy dodatkowych spotkań w Instytucie Informatyki, podczas których będzie można oddać zaległe rozwiązania oraz porozmawiać na tematy związane z kursem (ale nie tylko ;):

- poniedziałek 25.06, 8.30-10.30
- wtorek 26.06, 8.30-10.30

Miejsce: parter Instytutu


## Listy zadań

- [Lista 1](exercises/01-diamond-words.md)
- [Lista 2](exercises/02-money-value-object.md)
- [Lista 3](exercises/03-products.md)
- [Lista 4](exercises/04-rest-api.md)
- [Lista 5](exercises/05-cart-rules.md)
- [Lista 6](exercises/06-rpn-calculator.md)
- [Lista 7](exercises/07-money-wallet.md)
- [Lista 8](exercises/08-command-bus.md)
- [Lista 9](exercises/09-process-manager.md) [Termin: 25 maja]
- [Lista 10](exercises/10-database-repository.md)
- [Lista 11](exercises/11-database-performance.md)
- [Lista 12](exercises/12-web-performance.md)
- [Lista 13](exercises/13-automation.md)


## Notatki z wykładów

Lista notatek z poszczególnych wykładów, wraz z linkami do dodatkowych materiałów uzupełniających

- [Wykład 1, 23 luty 2018: Podstawy języka PHP, wprowadzenie do ekosystemu](notes/lectures/01-php-intro.md)
- [Wykład 2, 2 marzec 2018: Obiektowość, część 1](notes/lectures/02-objects.md)
- [Wykład 3, 9 marzec 2018: Obiektowość, część 2](notes/lectures/03-objects-continued.md)
- [Wykład 4, 16 marzec 2018: HTTP Flow](notes/lectures/04-http-flow.md)  
- [Wykład 5, 23 marzec 2018: Templates](notes/lectures/05-templates.md)
- [Wykład 6, 6 kwiecień 2018: Testy jednostkowe, TDD](notes/lectures/06-testing.md) 
- [Wykład 7, 13 kwiecień 2018: Modelowanie domeny, podejście zdarzeniowe](notes/lectures/07-domain-modeling-events.md)
- [Wykład 8, 20 kwiecień 2018: Modelowanie domeny, Event Storming](notes/lectures/08-domain-modeling-event-storming.md)
- [Wykład 9, 27 kwiecień 2018: Modelowanie, integracja](notes/lectures/09-modeling-integration.md)
- Wykład 10, 18 maj 2018: Bazy danych, część 1
- [Wykład 11, 25 maj 2018: Bazy danych, część 2](notes/lectures/11-databases-continued.md)
- [Wykład 12, 1 czerwiec 2018: Wydajność i skalowalność](notes/lectures/12-performance-and-scalability.md)
- [Wykład 13, 8 czerwiec 2018: Deployment aplikacji](notes/lectures/13-deployment.md)


## Literatura

### Elektroniczna

- Dokumentacja języka, http://php.net/manual/en/
- PHP The Right Way, http://www.phptherightway.com/
