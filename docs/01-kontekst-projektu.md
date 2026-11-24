# Kontekst projektu – System Miejskich Rowerów i Hulajnóg

## Opis i wizja systemu
Projekt zakłada stworzenie jednej, prostej aplikacji do obsługi wypożyczalni miejskich rowerów i hulajnóg. System pozwala użytkownikom na sprawdzenie dostępnych pojazdów w mieście, ich rezerwację, wypożyczenie oraz zwrot wraz z automatycznym naliczeniem opłaty za czas przejazdu.

Wizją systemu jest uproszczenie procesu wypożyczania pojazdów miejskich w jednym miejscu – bez zbędnych formalności. Z jednej aplikacji korzystają zarówno klienci (wypożyczający sprzęt), jak i administrator zarządzający flotą i cennikiem.

## Lista aktorów

* **Użytkownik (Klient)** – osoba zarejestrowana w systemie, która przegląda listę/mapę dostępnych rowerów i hulajnóg, wypożycza wybrany pojazd, kończy przejazd oraz opłaca go ze swojego konta w aplikacji.
* **Administrator** – zarządza bazą pojazdów (dodaje nowe, oznacza uszkodzone/niedostępne), ustala stawki za minutę jazdy oraz podgląda historię wszystkich wypożyczeń w systemie.
* **System płatności (zewnętrzny / symulowany)** – obsługuje doładowanie salda użytkownika oraz rozlicza opłatę po zakończeniu przejazdu.
