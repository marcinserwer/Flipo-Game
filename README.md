# Flipo - Twisted cards 
<h3 align="center">To dynamiczna i wciągająca gra karciana na telefon, oparta na zasadach klasycznego Uno. Jeśli masz ochotę na szybką i ekscytującą rozgrywkę z drugą osobą, ta aplikacja jest idealnym wyborem, zwłaszcza jeśli zależy Ci na intuicyjnym interfejsie i przyjaznym dla graczy podejściu. </h3>

## Przyszłe plany
- Dodać galerie NFT i możliwość kupowania skórek do kart
- Zapraszanie kolegów za pomocom kodu zaproszeń
- Obsługa czarnego motywu
- Granie w trzy i cztery osoby
- Muzyka która dynamicznie dopasowuje się do rozgrywki

## Postęp pracy 
### Wersja 0.1 (15.12.2022 - 07.01.2023, 10 dni pracy)
- Stworzono system losowania kart
- Stworzono tablicę przechowującą karty
- Stworzone osobne okno w którym będzie się dziać główna gra
- Stworzona na początkowym ekranie zapisywanie nazwy użytkownika
- Stworzenie czasu rzeczywistego połączenia z serwerem
- Błąd: Gdy jest sworzony pokój, automacznie uruchamia główną grę (powinno czekać na dołączenie gracza) (Naprawiono)
- Dodanie gdy zmieniamy nick, serwer usuwa z serwera poprzedni nick i dodaje nowy
- Dodanie oczekiwania na drugiego gracza w pokoju
- Dodano zabezpieczenie przed dołączeniem do swojego pokoju
- Zmieniono funkcję losowania kart, od teraz np. Karta plus 4 nie ma koloru ani numeru, lub zmiana strony nie ma teraz numeru.
- Dodano okno z konfiguracją meczu: ilość graczy (tylko 2) i ilość kart. Dodano w main_game ilość kart jest pobierana z serwera, komunikat gdy przeciwnik opuści gre i przechodzi do waiting_rooms
### Wersja 0.2 (08.01.2023 - TBA, 20 dni pracy)
- Dodano ilość kart dla drugiego gracza, wyświetlanie dynamicznie graficznych ilości kart przeciwnika, przerobiono funkcję gdzy przeciwnik opuści gre.
- Błąd: Podwójne komunikaty o "oczekiwaniu na gracza", gdy przeciwnik wychodzi z meczu pokazują się komunikaty o "oczekiwaniu na gracza" a nastepnie "gracz opuścił mecz"
- Błąd: Talia przeciwnika powinna być dla player2 jeśli jesteś player1 i na odwrót a nie tylko dla player2 (Naprawiono)
- Naprawiono błąd z pokazywaniem tali przeciwnika
- Dodano ikonkę gry
- Dodano losowanie głównej karty i wyświetlanie jej
- Tworzenie pierwszych kart
- Naprawiono crash gry po wyjściu gracza. 
- Błąd: Po wyjściu gracza z meczu pojawiają się komunikatu o oczekiwaniu na gracza a póżniej "Gracz opuścił mecz"
- Dodano przedstawienie graficznych kart
- Dodano dobieranie dodatkowych kart 
- Modyfikacja skryptu tworzącego główną kartę
- Rozpoczęto prace nad rzucaniem kart
- Dodano ruchy graczy, czyli kto aktulanie rzuca
- Zmodyfikowano kod dotyczący przechowywania kart
- Dodano komunikat o wygranym/przegranym meczu
- Błąd : Można rzucać karty jeśli główna karta jest np. zmiana strony i ma numer 0 to można rzucić byle jaką kartę która ma też numer 0 (Naprawiono)
- Błąd: Czasami zdarza się że karta Plus4, Plus2 dodaje karty sobie a nie przeciwnikowi (Naprawiono)
- Błąd: Można rzucić zmianę koloru gdy nawet poprzedni gracz nie wybrał koloru (Naprawiono)
- Błąd: Dobiera np. 6 kart, gdy gracz rzucił plus2 a następnie plus4 i przeciwnikowi nie dodawało 4 kart tylko 6 kart (Naprawiono)
- Dodano funkcję karty zmiana strony
- Nowa lekko zmieniona ikonka gry
- Dodano licznik czasowy odmierzający czas do końca ruchu gracza
- Optymalizacja kodu o 65 linijek
- Dobieranie karty po upływie czasu do rzutu karty
- Dodano funkcje blokady karty i odbijania jej (5 dni pracy)
- Błąd: Zamiast blokować na jedną kolejkę blokuje na dwie (Naprawiono)
- Błąd: Nie można odbijać blokady (Naprawiono)
- Błąd: Gdy rzuca się Plus4/Plus2 daje sobie dziwną ilość kart, lub przeciwnikowi (Naprawiono) 
- Błąd: Gdy odbija sie blokadę przeciwnika, powinien stać dwie kolejki a nie jedną (Naprawiono)
- Błąd: Czasem przy tworzeniu poczekalni zmienia samoczynnie się ilość kart, powinno być np. 8 a ustawia się na 1 lub 4 kart
- Błąd: Podczas odbijania blokady można rzucić zwykłą kartę zamiast tylko blokadę (Naprawiono)
- Dodać: Gdy gracz dobierze kartę i będzie można ją rzucić, pozwolić mu na to
