# Pokemon RPG Game

Projekt to gra RPG wzorowana na klasykach z konsoli Game Boy Advance. Aplikacja została zrealizowana w języku C++ z wykorzystaniem biblioteki SFML 2.6.2. Projekt zawiera podstawowe mechaniki rozgrywki oraz autorski edytor map. 

Gra posiada potencjał do dalszej rozbudowy lub wykorzystania jako baza do stworzenia bardziej zaawansowanego tytułu.

## Główne funkcjonalności

* Menu główne zawierające opcje: nowa gra, wczytanie zapisu, ustawienia (z przejściem do edytora) oraz wyjście.
* Możliwość wyboru początkowego pokemona i jego późniejszego rozwijania.
* System losowych spotkań z przeciwnikami ukrywającymi się w trawie.
* System walki pozwalający na ucieczkę lub użycie jednego z 4 dostępnych ataków w celu pokonania przeciwnika.
* System doświadczenia (EXP), w którym pokemon awansuje na kolejny poziom po zdobyciu punktów w ilości równej: 100 * aktualny poziom.
* Obsługa mechanik silnika, w tym praca kamery, odtwarzanie animacji oraz system kolizji.
* Menu pauzy (ESC) umożliwiające zapisanie stanu gry oraz wyjście do menu głównego.

## Wbudowany edytor map

W celu ułatwienia projektowania świata zaimplementowano dedykowany edytor map.

* Obsługa map opartych na kafelkach (tiles) generowanych przez podział pliku graficznego na fragmenty o wymiarach 50x50.
* Menu wyboru kafelków z możliwością jego ukrycia ("X") dla lepszej widoczności obszaru roboczego.
* Rozbudowane menu pauzy edytora pozwalające na zapis aktualnej mapy, wczytanie poprzednio zapisanej (w celu kontynuacji pracy) oraz wyjście do menu głównego.
* Format zapisu przechowujący rozmiar kafelków, ścieżkę do pliku .png oraz układ liczbowy reprezentujący mapę.

## Technologie

* Język programowania: C++
* Biblioteka graficzna: SFML 2.6.2
