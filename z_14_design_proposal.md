# Design Proposal

## Skład zespołu:
-
-
-


## Temat projektu
Rozwiązanie buga [*Line break within function declaration disables exclusion of the function
body*](https://github.com/nedbat/coveragepy/issues/684) w projekcie **coveragepy**.

## Stack technologiczny
- *python* >= 3.8
- biblioteki używane w **coveragepy** - [https://github.com/nedbat/coveragepy/tree/master/requirements](https://github.com/nedbat/coveragepy/tree/master/requirements)
- linter - *pylint*
- testy - *pytest*, *tox*
- środowisko wirtualne - *venv*

## Planowany zakres ekperymentów
Odtworzenie błędów zgłaszanych przez użytkowników biblioteki w celu znalezienia przyczyny buga. Identyfikacja źródła problemu i implementacja rozwiązania. Przetestowania działania na problemach użytkowników i wytworzonych przez nas testach zawierających przypadki brzegowe.

## Planowana funkcjonalność programu
Umożliwienie wykluczenia funkcji/klasy, której deklaracja zajmuje więcej niż jedną linię przy pomocy `[report] exclude_lines`.

## Harmonogram
- 30.10 - 5.11 - analiza problemu i istniejącej dokumentacji
- 06.11 - 12.11 - konfiguracja środowiska eksperymentalnego
- 13.11 - 19.11 - zapoznanie z projektem, odtworzenie problemów zgłaszanych przez użytkowników
- 20.11 - 26.11 - identyfikacja problemu
- 27.11 - 03.12 - wstępna implementacja
- 04.12 - 10.12 - przygotowanie testów, poprawki do implementacji
- 11.12 - 17.12 - uzupełnienie dokumentacji
- 18.12 - 20.12 - wystawienie PR
- 21.12 - 02.01 - przerwa świąteczna
- 03.01 - 07.01 - finalne poprawki, akceptacja PR

## Bibliografia
- issue z bugiem - [https://github.com/nedbat/coveragepy/issues/684](https://github.com/nedbat/coveragepy/issues/684)
- repozytorium **coveragepy** - [https://github.com/nedbat/coveragepy](https://github.com/nedbat/coveragepy)
- dokumnetacja **coveragepy** - [https://coverage.readthedocs.io](https://coverage.readthedocs.io), a w szczególności zasady kontrybucji do projektu - [https://coverage.readthedocs.io/en/latest/contributing.html](https://coverage.readthedocs.io/en/latest/contributing.html)
