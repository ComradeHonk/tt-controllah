
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
