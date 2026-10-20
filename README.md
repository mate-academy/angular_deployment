# Moonbase Control: Deployment

Zadanie z modułu Angular. Repozytorium zawiera kod startowy aplikacji Moonbase Control dla tej lekcji.

## Zadanie

#### Wdróż aplikację Moonbase Control
Moonbase Control jest już gotową aplikacją działającą lokalnie. Przygotuj jej wersję produkcyjną i opublikuj ją tak, aby była dostępna przez publiczny adres.

- Wykonaj produkcyjny build aplikacji za pomocą: `ng build`
- Upewnij się, że proces budowania zakończył się bez błędów.
- Odszukaj katalog zawierający pliki wygenerowane przez Angular CLI i sprawdź jego zawartość.
- Opublikuj wygenerowaną wersję aplikacji.
- Otwórz publiczny adres aplikacji i sprawdź, czy Moonbase Control uruchamia się poprawnie.
- Sprawdź działanie nawigacji pomiędzy dostępnymi ścieżkami aplikacji.
- Otwórz bezpośrednio jedną ze ścieżek aplikacji, np. `/missions`, i odśwież stronę.
- Upewnij się, że aplikacja nadal działa poprawnie i odświeżenie strony nie powoduje błędu 404.

💡 Aplikacja pobiera dane z lokalnego API (`localhost:4000`), które nie jest częścią wdrożenia. Po publikacji listy misji i incydentów mogą być puste. To oczekiwane. W tym zadaniu sprawdzamy build, publikację oraz działanie ścieżek aplikacji.

#### Oczekiwany rezultat
Aplikacja Moonbase Control:

- posiada poprawnie wykonany build produkcyjny,
- jest dostępna pod publicznym adresem,
- działa poprawnie podczas nawigacji pomiędzy widokami,
- działa poprawnie po bezpośrednim otwarciu i odświeżeniu poszczególnych ścieżek.

## Jak zacząć

1. Zrób fork tego repozytorium na swoje konto GitHub.
2. Sklonuj swój fork na komputer.
3. Zainstaluj zależności: `npm install`.
4. Uruchom aplikację: `npm start`.
5. Jeśli zadanie korzysta z danych z API, uruchom w drugim terminalu mock API: `npm run api`.

## Jak oddać zadanie

1. Dodaj publiczny adres wdrożonej aplikacji na początku tego pliku `README.md`.
2. Zapisz zmiany (adres i ewentualną konfigurację hostingu) w commicie i wypchnij je do swojego forka.
3. Otwórz Pull Request z forka do repozytorium `mate-academy/angular_deployment`, do brancha `main`. Wklej publiczny adres aplikacji także w opisie Pull Requesta.
4. Platforma uruchomi review Twojego Pull Requesta.
