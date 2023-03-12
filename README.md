# UNO Game
### Opis
- Stworzenie gry która spełni prawie każde upodobania
### Przyszłe plany
- Dodać galerie NFT i możliwość kupowania skórek do kart

### Postęp pracy 
1. Stworzono system losowania kart
2. Stworzono tablicę przechowującą karty
3. Stworzone osobne okno w którym będzie się dziać główna gra
4. Stworzona na początkowym ekranie zapisywanie nazwy użytkownika
#### 26.12.2022
- Stworzenie połączenia czasu rzeczywistego z serwerem, podczas uruchomienia aplikacji jest wysyłana nazwa użytkownika, stworzenie pokoju i możliwość dołączenia do niego.
- Błędy: Gdy jest sworzony pokój, automacznie uruchamia główną grę(powinno czekać na dołączenie gracza)

#### 27.12.2022
- Dodanie gdy zmieniamy nick, serwer usuwa z serwera poprzedni nick i dodaje nowy.

#### 30.12.2022
- Dodanie oczekiwania na drugiego gracza w pokoju
#### 05.01.2023
- Dodano zabezpieczenie przed dołączeniem do swojego pokoju
#### 06.01.2023
- Zmieniono funkcję losowania kart, od teraz np. Karta plus 4 nie ma koloru ani numeru, lub zmiana strony nie ma teraz numeru.
#### 07.01.2023
- Dodano okno z konfiguracją meczu: ilość graczy (tylko 2) i ilość kart. Dodano w main_game ilość kart jest pobierana z serwera, komunikat gdy przeciwnik opuści gre i przechodzi do waiting_rooms
#### 08.01.2023 Wersja 0.2!
- Dodano ilość kart dla drugiego gracza, wyświetlanie dynamicznie graficznych ilości kart przeciwnika, przerobiono funkcję gdzy przeciwnik opuści gre.
- Błędy: Podwójne komunikaty o "oczekiwaniu na gracza", gdy przeciwnik wychodzi z meczu pokazują się komunikaty o "oczekiwaniu na gracza" a nastepnie "gracz opuścił mecz", talia przeciwnika powinna być dla player2 jeśli jesteś player1 i na odwrót a nie tylko dla player2
#### 09.01.2023
- Naprawiono błąd z pokazywaniem tali przeciwnika
#### 20.01.2023
- Dodano ikonkę gry
#### 26.01.2023
- Dodano losowanie głównej karty i wyświetlanie jej
#### 27.01.2023
- Tworzenie pierwszych kart
#### 30.01.2023
- Naprawiono crash gry po wyjściu gracza. Praca nad naprawieniem błedu "Po wyjściu gracza z meczu pojawiają się komunikatu o oczekiwaniu na gracza a póżniej gracz opuścił mecz"
####12.03.2023
- Dodano przedstawienie graficzne kart v1
