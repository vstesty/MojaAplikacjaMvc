# MojaAplikacjaMvc

Prosta aplikacja ASP.NET Core MVC z interaktywnym schedulerem wydarzeń.

## Uruchomienie

Wymagany jest .NET 8 SDK. W katalogu projektu wykonaj:

```bash
dotnet run
```

Następnie otwórz adres podany w konsoli.

## Scheduler

Widok główny pokazuje hierarchię Projects → Project → People → Events. Każdy projekt może zawierać wiele osób, a każda osoba wiele wydarzeń. Przyciski przy elementach pozwalają je dodawać, zmieniać ich nazwy i usuwać; usunięcie projektu lub osoby usuwa też ich elementy podrzędne. Kliknij wydarzenie, aby je edytować lub usunąć. Przeciągnij je na inny dzień, aby zmienić datę, albo do wiersza innej osoby, aby zmienić przypisanie. Suwak „Miesiące” ustawia zakres od 1 do 12 miesięcy, a „Skala” pozwala dopasować ich szerokość; kalendarz można przewijać poziomo. Nowe elementy i zmiany są przechowywane tylko do odświeżenia strony.
