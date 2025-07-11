# DOJ Application Portal - README (po polsku)

Demo strony:
https://sites.google.com/view/ldepartment-of-justice?usp=sharing

## Przegląd
To repozytorium zawiera responsywną aplikację internetową dla Departamentu Sprawiedliwości USA, która udostępnia trzy kluczowe formularze aplikacyjne:
1. Wniosek o pozwolenie na ukryte noszenie broni (CCW)
2. Wniosek o dotację dla małej firmy
3. Wniosek o dotację dla agencji ścigania

## Funkcje
- **Responsywny design** działa na komputerach i urządzeniach mobilnych
- **Nawigacja zakładkami** między różnymi typami wniosków
- **Walidacja formularzy** dla pól wymaganych
- **Integracja z Discordem** do przesyłania zgłoszeń
- **Oficjalny wygląd** z kolorystyką i brandingiem DOJ

## Wymagania
Do uruchomienia aplikacji lokalnie potrzebujesz tylko:
- Nowoczesnej przeglądarki internetowej (Chrome, Firefox, Safari, Edge)
- Aktywnego połączenia internetowego (dla integracji z Discordem)

## Instalacja
Nie wymaga instalacji! Po prostu otwórz plik `index.html` w przeglądarce.

## Konfiguracja
Aby włączyć powiadomienia na Discordzie:
1. Stwórz adres URL webhooka na Discordzie
2. Zastąp placeholder w kodzie JavaScript:
```javascript
const webhookURL = 'https://discord.com/api/webhooks/...'; // Zastąp prawdziwym adresem webhooka Discord
```

## Użycie
1. Otwórz plik `index.html` w przeglądarce
2. Wybierz odpowiednią zakładkę aplikacji:
   - Wniosek o pozwolenie CCW
   - Wniosek o dotację dla firmy
   - Wniosek o dotację dla agencji
3. Wypełnij wszystkie wymagane pola (oznaczone *)
4. Kliknij "SUBMIT APPLICATION" aby wysłać wniosek

## Szczegóły formularzy

### Wniosek o pozwolenie CCW
- Sekcja danych osobowych
- Pytania o przeszłość kryminalną
- Uzasadnienie wniosku
- Oświadczenie i podpis

### Wniosek o dotację dla firmy
- Informacje o firmie
- Dane właściciela
- Szczegóły dotacji
- Operacje biznesowe

### Wniosek o dotację dla agencji
- Informacje o agencji
- Dane wnioskodawcy
- Szczegóły dotacji
- Informacje o zatrudnieniu

## Uwagi prawne
Ta aplikacja jest fikcyjnym projektem demonstracyjnym i nie jest powiązana z prawdziwym Departamentem Sprawiedliwości USA.
