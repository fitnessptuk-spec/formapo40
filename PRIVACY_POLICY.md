# Polityka prywatności — Forma po 40

Data ostatniej aktualizacji: 10.06.2026

Niniejsza polityka prywatności opisuje, w jaki sposób aplikacja **Forma po 40** ("Aplikacja") obsługuje dane użytkownika.

## 1. Najważniejsze w skrócie

- Aplikacja działa **w 100% offline** — nie wymaga połączenia z internetem.
- Aplikacja **nie wymaga zakładania konta ani logowania**.
- Aplikacja **nie zbiera, nie przechowuje na serwerach i nie udostępnia** żadnych danych osobowych.
- Wszystkie wprowadzone dane pozostają **wyłącznie na urządzeniu użytkownika**.
- Aplikacja **nie zawiera reklam, narzędzi analitycznych ani śledzących (np. Google Analytics, Firebase, Crashlytics)**.

## 2. Jakie dane są przetwarzane i gdzie są przechowywane

W ramach korzystania z Aplikacji użytkownik może wprowadzić:

- historię ukończonych treningów (data, wybrany protokół, czas trwania),
- wpisy do dziennika wskaźników: obwód pasa, masa ciała, ciśnienie krwi, tętno spoczynkowe, ocena energii i snu, opcjonalna notatka o dolegliwości,
- ustawienia przypomnienia (włączone/wyłączone, godzina).

Wszystkie powyższe dane są zapisywane **wyłącznie lokalnie**, w lokalnej bazie danych na urządzeniu (Room/SQLite) oraz w lokalnych preferencjach aplikacji. Dane te:

- nie są wysyłane do twórcy Aplikacji ani do jakichkolwiek osób trzecich,
- nie opuszczają urządzenia użytkownika w żadnym automatycznym procesie,
- są usuwane automatycznie wraz z odinstalowaniem Aplikacji lub mogą zostać wcześniej wyczyszczone przez użytkownika ręcznie (ustawienia systemowe → aplikacje → Forma po 40 → wyczyść dane).

## 3. Udostępnianie danych przez użytkownika

Aplikacja umożliwia wygenerowanie graficznej "karty miesięcznej" z podsumowaniem postępów (np. liczba treningów, streak, zmiana obwodu pasa) i jej udostępnienie za pomocą **systemowego okna udostępniania Androida** (np. do mediów społecznościowych, komunikatora, e-maila).

- Wygenerowanie i udostępnienie karty następuje **wyłącznie z inicjatywy użytkownika** po naciśnięciu przycisku "Pochwal się".
- Twórca Aplikacji nie ma dostępu do tej karty ani informacji o tym, czy i gdzie została udostępniona — cały proces odbywa się lokalnie, za pośrednictwem aplikacji wybranej przez użytkownika z systemowego menu.
- Plik graficzny jest tymczasowo zapisywany w katalogu pamięci podręcznej Aplikacji i służy wyłącznie do przekazania go wybranej aplikacji docelowej.

## 4. Uprawnienia wykorzystywane przez Aplikację

| Uprawnienie | Cel wykorzystania |
|---|---|
| **Wibracje** (`VIBRATE`) | Sygnalizacja dotykowa podczas treningu (zmiana ćwiczenia, odliczanie końcowe, zakończenie sesji). |
| **Powiadomienia** (`POST_NOTIFICATIONS`) | Wyświetlenie opcjonalnego, codziennego przypomnienia o treningu — wyłącznie jeśli użytkownik włączy tę funkcję. |
| **Uruchomienie po restarcie** (`RECEIVE_BOOT_COMPLETED`) | Ponowne ustawienie zaplanowanego przypomnienia po ponownym uruchomieniu telefonu lub aktualizacji Aplikacji — wyłącznie jeśli przypomnienie było wcześniej włączone. |

Żadne z powyższych uprawnień nie jest wykorzystywane do zbierania, przesyłania ani udostępniania danych.

## 5. Przypomnienia (powiadomienia lokalne)

Funkcja przypomnień działa w całości lokalnie przy użyciu mechanizmów systemu Android (`AlarmManager`, lokalne powiadomienia). Aplikacja sprawdza lokalnie zapisaną historię treningów, aby nie wyświetlać przypomnienia, jeśli trening na dany dzień został już ukończony. Żadne dane nie są przy tym wysyłane na zewnątrz.

## 6. Dzieci

Aplikacja jest skierowana do osób dorosłych (40+) i nie jest przeznaczona dla dzieci. Aplikacja nie zbiera żadnych danych, w tym danych dzieci.

## 7. Zmiany w polityce prywatności

W przypadku wprowadzenia zmian w Aplikacji wpływających na sposób przetwarzania danych, niniejsza polityka zostanie odpowiednio zaktualizowana wraz ze zmianą daty na początku dokumentu.

## 8. Kontakt

W razie pytań dotyczących niniejszej polityki prywatności, prosimy o kontakt pod adresem:

**fitnessptuk@gmail.com**
