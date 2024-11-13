# Trello-REST-API

## Opis projektu
Ten projekt zawiera zestaw testów API opracowanych przy użyciu Postmana. Celem jest zautomatyzowanie testów API oraz zapewnienie, że poszczególne endpointy działają zgodnie z oczekiwaniami. Skrypty testowe obejmują podstawowe testy funkcjonalne.

## Wymagania
Aby rozpocząć pracę z tym projektem, potrzebujesz:

- Zainstalowanego Postmana (zalecana wersja: najnowsza dostępna na stronie Postmana)
- Konto na Postmanie (opcjonalnie, jeśli chcesz synchronizować kolekcje i dane testowe)
- Środowisko API do przetestowania (serwer, na którym są dostępne endpointy API)
- 
## Zawartość
- Kolekcja testów Postman – Zawiera zestaw endpointów, na których wykonywane są testy.
- Środowisko Postmana – Definiuje zmienne środowiskowe (takie jak URL serwera API, tokeny autoryzacyjne itp.), które są wykorzystywane w testach.
- Skrypty testowe – W sekcji Tests w Postmanie znajdują się skrypty, które automatyzują testowanie odpowiedzi API, weryfikują kody statusu oraz poprawność danych.

## Funkcje projektu
- Testowanie funkcjonalności – Weryfikacja poprawnych odpowiedzi na żądania GET, POST, PUT i DELETE.
- Walidacja danych – Sprawdzenie, czy struktura odpowiedzi JSON zawiera wymagane pola oraz czy wartości odpowiadają oczekiwanym wynikom.
- Autoryzacja – Testy weryfikujące poprawność tokenów autoryzacyjnych i dostęp do chronionych zasobów.
- Assercje i walidacja statusów HTTP – Automatyczna walidacja kodów statusu odpowiedzi oraz zwracanych błędów.
