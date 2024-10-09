# "Test_Playwright_CSharp"

## Program nauki na automatyzującego testera oprogramowania z wykorzystaniem Playwright i C#
### Czas trwania: 2 miesiące (6 dni nauki, 1 dzień odpoczynku w tygodniu)
### Czas nauki dziennie: 5 godzin

### Cel programu:
Nauczenie się automatyzacji testów oprogramowania webowego z wykorzystaniem języka C# oraz frameworka Playwright. Po zakończeniu programu będziesz potrafił samodzielnie pisać testy automatyczne, rozumieć procesy testowe oraz stosować najlepsze praktyki w testowaniu aplikacji webowych.

1. Oprogramowanie do zainstalowania:
- Visual Studio 2022 (Community Edition)
    Download: https://visualstudio.microsoft.com/downloads/
    - Potrzebne składniki: .NET desktop development, ASP.NET, testowanie jednostkowe
2. .NET SDK (aktualna wersja, jeśli nie instalujesz z Visual Studio)
- Download: https://dotnet.microsoft.com/download/dotnet
3. Playwright for C#
- Dostępny przez NuGet w Visual Studio.
4. NUnit (lub xUnit) jako framework do testowania jednostkowego
- Również dostępny przez NuGet w Visual Studio.
5. Git
- Do zarządzania wersjami i repozytoriów kodu.
    - Download: https://git-scm.com/
6. Postman lub Insomnia (do testowania API)
- Download Postman: https://www.postman.com/downloads/



# Plan nauki:

## Tydzień 1: Podstawy C# i środowiska Visual Studio

## Dzień 1: Instalacja i konfiguracja środowiska

- Instalacja Visual Studio, .NET SDK, Git.
- Tworzenie pierwszego projektu C# w Visual Studio.
- Zrozumienie struktury projektu .NET.
- Praca z Git: tworzenie repozytorium, commit, push, pull.

## Dzień 2: Podstawy C#

- Zmienne, typy danych, operatory, kontrola przepływu (if, switch).
- Pętla for, while, do-while.
- Tworzenie pierwszych prostych aplikacji konsolowych.

## Dzień 3: Podstawy C# c.d.

- Funkcje i metody.
- Parametry, wartości zwracane, przeciążanie metod.
- Struktury i klasy.

## Dzień 4: Programowanie obiektowe w C#

- Klasy, dziedziczenie, polimorfizm, interfejsy.
- Praca z właściwościami, konstruktorami i metodami.
- Zasady SOLID i ich znaczenie w kodzie testów.

## Dzień 5: Praktyczne ćwiczenia z OOP w C#

- Tworzenie prostych klas i implementacja dziedziczenia.
- Zastosowanie zasad SOLID w praktyce.

## Dzień 6: Kolekcje i zarządzanie danymi

- List, Dictionary, HashSet, Queue, Stack.
- Praca z kolekcjami w kontekście testów.


## Tydzień 2: Podstawy testów jednostkowych z NUnit

## Dzień 1: Wprowadzenie do testowania jednostkowego

- Rola testów jednostkowych.
- Test-Driven Development (TDD) – co to jest i jak działa?
- Tworzenie pierwszych testów jednostkowych w NUnit.

## Dzień 2: NUnit w praktyce

- Instalacja i konfiguracja NUnit w Visual Studio.
- Tworzenie testów jednostkowych.
- Asercje w NUnit (Assert.AreEqual, Assert.IsTrue, Assert.IsFalse).

## Dzień 3: Parametryzacja testów

- Tworzenie testów z różnymi przypadkami testowymi.
- Użycie atrybutów TestCase i TestFixture.

## Dzień 4: Zaawansowane techniki testowania

- Testowanie wyjątków.
- Mockowanie danych (wprowadzenie do narzędzi jak Moq).

## Dzień 5: Organizacja testów jednostkowych

- Jak organizować testy w większych projektach.
- Konfiguracja i cleanup (SetUp, TearDown).

## Dzień 6: Refaktoryzacja i optymalizacja testów

- Przegląd zasad DRY (Don’t Repeat Yourself) i ich zastosowanie.
- Optymalizacja kodu testów.


## Tydzień 3: Wprowadzenie do Playwright

## Dzień 1: Wprowadzenie do Playwright

- Co to jest Playwright?
- Instalacja Playwright przez NuGet w Visual Studio.
- Pierwsze kroki: konfiguracja projektu.

## Dzień 2: Uruchamianie testów Playwright

- Tworzenie pierwszego testu w Playwright.
- Uruchamianie przeglądarki, nawigacja po stronie, interakcje z elementami.
- Wprowadzenie do BrowserType (Chromium, Firefox, WebKit).

## Dzień 3: Znajdowanie i manipulowanie elementami

- Lokalizatory elementów (XPath, CSS).
- Klikanie, wypełnianie formularzy, interakcje z przyciskami i linkami.
- Przykłady praktyczne.

## Dzień 4: Tworzenie testów E2E (End-to-End)

- Pisanie pełnych testów E2E w Playwright.
- Scenariusze logowania, nawigacji i interakcji z dynamicznymi elementami.

## Dzień 5: Debugowanie testów

- Narzędzia do debugowania testów w Playwright (np. tryb "headed", zrzuty ekranu, video).
- Praktyczne debugowanie testów z użyciem Playwright Inspector.

## Dzień 6: Synchronizacja w Playwright

- Implicit wait vs explicit wait.
- Czekanie na elementy: waitForSelector, waitForLoadState, waitForTimeout.
- Rozwiązywanie problemów z synchronizacją testów.


## Tydzień 4: Zaawansowane tematy Playwright

## Dzień 1: Page Object Model (POM)

- Wprowadzenie do Page Object Model (POM).
- Implementacja POM w testach Playwright.
- Refaktoryzacja kodu według POM.

## Dzień 2: Testowanie różnych przeglądarek i urządzeń

- Konfiguracja testów dla różnych przeglądarek (Chromium, Firefox, WebKit).
- Testowanie na urządzeniach mobilnych.
- Emulacja urządzeń i rozdzielczości.

## Dzień 3: Testowanie responsywnych aplikacji

- Symulowanie i testowanie na różnych urządzeniach (desktop, tablet, mobile).
- Przykłady testów dla aplikacji responsywnych.

## Dzień 4: Obsługa dynamicznych elementów i okien modalnych

- Interakcje z dynamicznymi stronami.
- Praca z modalami, popupami, oknami dialogowymi.
- Przykłady testów.

## Dzień 5: Tworzenie testów równoległych

- Wykonywanie testów równolegle w Playwright.
- Konfiguracja testów w trybie headless oraz headed.
- Użycie Playwright Test do konfiguracji testów równoległych.

## Dzień 6: Zapis i analiza wyników testów

- Generowanie raportów z testów.
- Zapisywanie zrzutów ekranu i nagrań wideo z nieudanych testów.
- Przykłady automatyzacji zapisów wyników testów.


## Tydzień 5: Testowanie API i integracja z Playwright

## Dzień 1: Wprowadzenie do testowania API

- Co to jest API?
- Rodzaje API (REST, SOAP).
- Tworzenie pierwszych testów API w Postman/Insomnia.

## Dzień 2: Testowanie API z Playwright

- Użycie Playwright do testowania API.
- Tworzenie zapytań HTTP (GET, POST, PUT, DELETE).
- Walidacja odpowiedzi HTTP w testach.

## Dzień 3: Złożone testy API

- Testowanie API z autoryzacją.
- Przykłady testowania API w złożonych scenariuszach.

## Dzień 4: Integracja testów API i E2E

- Tworzenie testów E2E, które integrują testy API i interfejsu użytkownika.
- Przykłady zastosowań.

## Dzień 5: Mockowanie odpowiedzi API

- Mockowanie API w testach.
- Użycie Playwright do symulacji odpowiedzi z API.

## Dzień 6: Optymalizacja testów API

- Tworzenie wydajnych testów API.
- Optymalizacja czasu wykonywania testów.


## Tydzień 6: Integracja z CI/CD, refaktoryzacja, i najlepsze praktyki

## Dzień 1: Wprowadzenie do CI/CD

- Co to jest CI/CD?
- Konfiguracja GitHub Actions / Azure DevOps do automatyzacji testów.

## Dzień 2: Integracja testów Playwright z CI/CD

- Tworzenie pipeline’u CI/CD do uruchamiania testów Playwright.
- Wykonywanie testów automatycznych przy każdym commitcie.

## Dzień 3: Refaktoryzacja kodu

- Jak refaktoryzować kod testów, aby był bardziej skalowalny i czytelny.
- Zastosowanie wzorców projektowych w testach automatycznych.

## Dzień 4: Najlepsze praktyki w testach automatycznych

- Pisanie testów, które są szybkie, stabilne i łatwe do utrzymania.
- Unikanie typowych problemów w automatyzacji testów.

## Dzień 5: Testowanie długofalowe i zarządzanie testami

- Jak zarządzać rosnącą bazą testów.
- Strategie utrzymania jakości testów.

## Dzień 6: Podsumowanie i projekt końcowy

- Tworzenie pełnego projektu testowego w Playwright.
- rzeprowadzenie testów E2E, API, oraz równoległych.
- Analiza wyników.


### Podsumowanie:
Po zakończeniu tego kursu powinieneś mieć dobrą znajomość C#, testów jednostkowych (NUnit), automatyzacji testów za pomocą Playwright oraz umiejętność integracji testów z systemami CI/CD. Dzięki temu będziesz mógł efektywnie pracować jako tester automatyzujący oprogramowanie w środowisku .NET i C#.

