# Rekrutacja - backend developer - Emako.pl
Proszę utworzyć repozytorium GIT, w którym zamieszczone zostaną rozwiązania poniższych zadań:

## Zadanie 1
Proszę napisać w Pythonie 3.x działający w konsoli skrypt, który dla określonej parametrami wejściowymi
lokalizacji (domyślnie: Wrocław) oraz daty (domyślnie: aktualny dzień) pobierze z jednego
z ogólnodostępnych API pogodowych dane odnośnie temperatury powietrza oraz opadów. Dla
optymalizacji pod kątem zmniejszenia liczby requestów warto wykorzystać np. bazę danych jako
pamięć podręczną (cache) skryptu. W przypadku braku lub wprowadzenia nieprawidłowych parametrów
skrypt powinien informować, w jaki sposób użyć go poprawnie. Jeżeli parametry są prawidłowe, to efektem działania
programu powinno być wypisanie wspomnianych danych pogodowych w czytelnej formie na standardowe wyjście, chyba że
wprowadzono w parametrze nazwę pliku docelowego - w takim wypadku należy zapisać te dane w tym pliku w formacie CSV.

## Zadanie 2
Proszę pobrać [skrypt _fuzzy-code.py_](fuzzy-code.py) a następnie zoptymalizować go pod kątem czytelności kodu,
odporności na błędy, wydajności itp. URL-e zawarte w nim są fałszywe, więc uruchomienie go nie spowoduje
żadnego efektu, zamiast tego należy samodzielnie przeanalizować jego przeznaczenie i zrefaktoryzować kod.
