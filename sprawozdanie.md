
| Wydział Informatyki Politechniki Białostockiej <br><br>Inżynieria Oprogramowania<br>Informatyka, Semestr IV, PS #1                              | Data przekazania:                            |
| ----------------------------------------------------------------------------------------------------------------------------------------------- | -------------------------------------------- |
| **Projekt**: System zarządzania zawodami w tenisa stołowego<br>**Zespół**:<br>- Marcel Alefierowicz<br>- Przemysław Dudek<br>- Michał Burzyński | **Prowadzący**:<br>dr. inż Marcin Czajkowski |

**Repozytorium GitHub:** [tt-controllah](https://github.com/ComradeHonk/tt-controllahh)

# 1. Treść zadania

Celem projektu jest zaprojektowanie systemu informatycznego wspierającego organizację zawodów w tenisa stołowego. System ma usprawnić proces zarządzania turniejami poprzez automatyzację planowania rozgrywek, obsługi uczestników oraz publikacji wyników.

Zakres projektu obejmuje funkcjonalności związane z tworzeniem i konfiguracją turniejów, rejestracją zawodników oraz generowaniem harmonogramu meczów. System umożliwia automatyczne tworzenie drabinek turniejowych (np. pucharowych lub grupowych), przypisywanie spotkań do dostępnych stołów oraz zarządzanie przebiegiem rozgrywek w czasie rzeczywistym. Dodatkowo przewiduje się możliwość wprowadzania wyników meczów przez sędziów oraz ich natychmiastową aktualizację w systemie.

Projekt obejmuje także funkcje przeglądania harmonogramu, sprawdzania wyników oraz informowania uczestników o nadchodzących meczach i zmianach organizacyjnych. System ma wspierać organizatora w nadzorowaniu przebiegu zawodów oraz zapewniać uczestnikom szybki dostęp do aktualnych informacji.

# 2. Cel, zakres, kontekst i korzyści

## 2.1 Cel budowania systemu

Celem projektowanego systemu jest stworzenie narzędzia informatycznego wspierającego planowanie oraz zarządzanie zawodami w tenisa stołowego. 

System ma umożliwiać sprawną organizację turniejów poprzez automatyzację kluczowych procesów, takich jak rejestracja zawodników, tworzenie harmonogramu rozgrywek, zarządzanie meczami oraz publikacja wyników. Głównym założeniem jest eliminacja problemów wynikających z ręcznego zarządzania zawodami (np. błędów w harmonogramie, opóźnień, braku aktualnych informacji), a także zwiększenie przejrzystości i efektywności organizacyjnej.

## 2.2. Zakres systemu

### 2.2.1 Zakres funkcjonalny

**System obejmuje następujące funkcjonalności:**

- tworzenie i konfiguracja turniejów (np. typ rozgrywek, liczba stołów),
- rejestracja i zarządzanie zawodnikami,
- generowanie drabinek turniejowych (pucharowych, grupowych),
- automatyczne planowanie harmonogramu meczów,
- przypisywanie meczów do stołów i przedziałów czasowych,
- wprowadzanie i zatwierdzanie wyników meczów,
- aktualizacja drabinki i postępu turnieju w czasie rzeczywistym,
- przegląd harmonogramu i wyników przez użytkowników,
- wysyłanie powiadomień o meczach i zmianach,
- generowanie raportów końcowych.

### 2.2.2 Zakres niefunkcjonalny
- dostępność systemu w trakcie zawodów (wysoka niezawodność),
- czas odpowiedzi systemu poniżej 2 sekund,
- obsługa wielu użytkowników jednocześnie,
- bezpieczeństwo danych użytkowników,
- dostępność na urządzeniach mobilnych.

## 2.3. Kontekst systemu

System funkcjonuje jako centralna platforma wspierająca organizację turnieju.

### 2.3.1 Aktorzy systemu (4):
1. Organizator – zarządza turniejem i jego przebiegiem  
2. Zawodnik – uczestniczy w zawodach i przegląda informacje  
3. Sędzia – wprowadza wyniki meczów  
4. System powiadomień – wysyła komunikaty do użytkowników  

System może współpracować z zewnętrznymi usługami (np. e-mail/SMS) w celu realizacji powiadomień.

## 2.4. Przewidywalne mierzalne korzyści

### 2.4.1 Skrócenie czasu przygotowania turnieju

- przed wdrożeniem: 4–6 godzin  
- po wdrożeniu: ok. 30 minut  

### 2.4.2 Redukcja liczby błędów w harmonogramie / podczas zapisywania użytkowników

- metryka: liczba błędów / turniej  
- przed: 10–15  
- po: 0–2  

### 2.4.3 Skrócenie czasu publikacji wyników

- przed: 10–15 minut  
- po: <10 sekund  

### 2.4.4 Wzrost liczby obsługiwanych zawodników

- przed: 64 zawodników  
- po: 96 zawodników  

# 3. Słownik

**Turniej**<br>
Zdarzenie sportowe obejmujące zestaw rozgrywek pomiędzy zawodnikami według określonego systemu.

**Zawodnik**<br>
Osoba biorąca udział w turnieju.

**Klub**<br>
Jednostka organizacyjna zrzeszająca zawodników.

**Mecz**<br>
Jednostka rywalizacji pomiędzy dwoma zawodnikami. Składa się z setów.

**Set**<br>
Część meczu, rozgrywana do określonej liczby punktów (np. 11).

**Punkt**<br>
Najmniejsza jednostka punktacji przyznawana w trakcie seta.

**Wynik meczu**<br>
Rezultat meczu wyrażony najczęściej liczbą wygranych setów przez zawodników.

**Faza turnieju**<br>
Logiczny etap turnieju (np. grupowa, pucharowa).

**Grupa**<br>
Zbiór zawodników w fazie grupowej, rywalizujących systemem „każdy z każdym”.

**Runda**<br>
Etap w fazie pucharowej (np. ćwierćfinał, półfinał).

**Drabinka turniejowa**<br>
Struktura odwzorowująca przebieg fazy pucharowej i zależności między meczami.

**System rozgrywek**<br>
Zasady organizacji turnieju (np. grupowy, pucharowy, mieszany).

**Ranking**<br>
Uporządkowana lista zawodników według wyników lub punktów.

**Rozstawienie (seedowanie)**<br>
Przypisanie zawodników do pozycji startowych w drabince na podstawie rankingu.

**Walkower**<br>
Specjalny przypadek zakończenia meczu bez rozegrania.

**Stół**<br>
Zasób fizyczny, na którym rozgrywany jest mecz.
