# GitHub Repository Search

## Opis

GitHub Repository Search to aplikacja stworzona w Pythonie, która pozwala na wyszukiwanie repozytoriów GitHub według nazwy użytkownika. Aplikacja umożliwia także zarządzanie historią wyszukiwań oraz dostosowanie motywów kolorystycznych.

## Funkcje

- Wyszukuje repozytoria GitHub na podstawie nazwy użytkownika.
- Wyświetla szczegóły repozytoriów: nazwa, opis, URL.
- Przechowuje historię wyszukiwań.
- Umożliwia zmianę motywów kolorystycznych (ciemny, jasny, kolorowy).
- Obsługuje błędy autoryzacji związane z tokenem dostępu.

## Jak uruchomić

1. **Zainstaluj wymagane biblioteki**:
   - Upewnij się, że masz zainstalowane biblioteki `requests` i `tkinter`.
   - Możesz użyć instalatora bibliotek.

2. **Utwórz plik**:
   - Otwórz edytor tekstu i wklej kod z aplikacji wyszukiwarki repozytoriów GitHub.
   - Zapisz plik jako `github_repo_search.py`.

3. **Uruchom skrypt**:
   - Otwórz terminal lub wiersz poleceń.
   - Przejdź do katalogu, w którym zapisałeś plik `github_repo_search.py`.
   - Uruchom skrypt za pomocą polecenia:
     ```sh
     python github_repo_search.py
     ```

## Wymagania

- Python 3.x
- Tkinter (dołączony do standardowej biblioteki Pythona)
- `requests` (do pobierania danych z API GitHub)

