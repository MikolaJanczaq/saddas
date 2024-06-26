# Noodle Project

## Opis

Noodle to aplikacja webowa stworzona do zarządzania [wstaw opis aplikacji]. Projekt wymaga serwera lokalnego oraz bazy danych, które można skonfigurować za pomocą XAMPP.

## Wymagania systemowe

Aby uruchomić Noodle, komputer musi spełniać następujące wymagania systemowe:

### XAMPP
- System operacyjny: Windows 2008, 2012, Vista, 7, 8 (ważne: XP ani 2003 nie są wspierane)
- [Minimalne wymagania dla XAMPP](https://www.apachefriends.org/index.html)

### Przeglądarka internetowa (np. Google Chrome)
- System operacyjny: Windows 10 lub nowszy albo Windows Server 2016 lub nowszy
- Procesor: Intel Pentium 4 lub nowszy, obsługujący SSE3
- [Minimalne wymagania dla Google Chrome](https://support.google.com/chrome/a/answer/7100626?hl=pl)

## Instrukcja obsługi

Aby uruchomić projekt Noodle na swoim komputerze, postępuj zgodnie z poniższymi krokami:

### Krok 1: Pobierz i zainstaluj XAMPP
1. Pobierz XAMPP ze strony [Apache Friends](https://www.apachefriends.org/index.html).
2. Zainstaluj XAMPP na swoim komputerze, postępując zgodnie z instrukcjami instalatora.

### Krok 2: Uruchom XAMPP i wystartuj Apache oraz MySQL
1. Otwórz XAMPP Control Panel.
2. Kliknij "Start" przy Apache oraz MySQL.

### Krok 3: Skonfiguruj bazę danych
1. W XAMPP Control Panel, kliknij "Admin" przy MySQL, aby otworzyć phpMyAdmin.
2. W phpMyAdmin utwórz nową bazę danych o nazwie `baza`.
3. Zaimportuj wybraną bazę danych z pliku projektowego (plik .sql).
4.     - Jeśli chcesz użyć pustej bazy danych, wybierz plik `czysta_baza.sql`. <!-- Uwaga: Należy pamiętać o uzupełnieniu bazy rekordami w odpowiednich tablicach przed rozpoczęciem pracy aplikacji. -->


### Krok 4: Skopiuj pliki projektu
1. Skopiuj folder z aplikacją o nazwie `strona` z paczki projektu.
2. Wklej folder `strona` do folderu `htdocs` w katalogu instalacyjnym XAMPP (zazwyczaj `C:\xampp\htdocs`).

### Krok 5: Uruchom aplikację w przeglądarce
1. Otwórz przeglądarkę internetową (np. Google Chrome).
2. W pasku adresu wpisz `http://localhost/strona` i naciśnij Enter.

Aplikacja powinna się uruchomić, umożliwiając korzystanie z funkcji Noodle.

## Kontakt
Jeżeli napotkasz problemy lub masz pytania, skontaktuj się z nami na [adres email] lub odwiedź naszą stronę na GitHubie.

---

Dziękujemy za korzystanie z Noodle!
