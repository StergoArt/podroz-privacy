# Polityka Prywatności — Podróż Dookoła Zdrowia

**Ostatnia aktualizacja:** 27 kwietnia 2026  
**Wersja aplikacji:** 1.0+  
**Twórca:** Stergo (Artek)  
**Kontakt:** artek29i@gmail.com

---

## Streszczenie (TL;DR)

Aplikacja **„Podróż Dookoła Zdrowia”** to gra edukacyjna dla dzieci. **Nie zbiera, nie przechowuje ani nie udostępnia żadnych danych osobowych.** Cała aktywność użytkownika (postęp w grze, odznaki, ukończone lekcje, wybrana skórka) jest przechowywana **wyłącznie lokalnie** na urządzeniu — w pamięci telefonu lub tabletu, do której nie mamy zdalnego dostępu.

Aplikacja działa **offline-first** — nie wykonuje połączeń sieciowych w czasie rozgrywki. Jedynym wyjątkiem są aktualizacje (OTA), opisane niżej.

---

## Jakie dane są zbierane?

### Dane przechowywane lokalnie (na urządzeniu)

Aplikacja zapisuje na urządzeniu użytkownika:
- **Imię** wpisane podczas rejestracji w grze (pole tekstowe)
- **Postęp w grze:** ukończone lekcje, quizy, minigry, zdobyte odznaki, pieczątki, wybrana postać Kompasika
- **Statystyki:** liczba dni gry pod rząd (streak), zdobyte XP i monety
- **Ustawienia:** włączone/wyłączone dźwięki, muzyka, powiadomienia
- **Obrazy postępu:** odblokowane karty z encyklopedii zdrowia

Dane te są zapisywane w lokalnych bazach (SQLite + MMKV) i **nigdy nie opuszczają urządzenia**. Nie są synchronizowane z chmurą, nie są wysyłane do żadnego serwera.

### Dane NIE zbierane

- Lokalizacja
- Kontakty
- Kalendarz
- Zdjęcia (z wyjątkiem zapisu certyfikatu ukończenia kursu — patrz niżej)
- Mikrofon, kamera
- Identyfikatory reklamowe
- Adres IP
- Adres e-mail dziecka
- Dane biometryczne
- Historia korzystania z innych aplikacji

---

## Połączenia sieciowe

### 1. Aktualizacje aplikacji (OTA)

Aplikacja sprawdza dostępność aktualizacji przy każdym uruchomieniu poprzez usługę **Expo Updates** (`https://u.expo.dev/`). Podczas tego sprawdzenia przesyłany jest:
- Identyfikator aplikacji (statyczny — nie identyfikuje użytkownika)
- Wersja zainstalowanej aplikacji
- Anonimowy identyfikator urządzenia generowany przez Expo (NIE jest to IDFA/AdID)

Te dane są wykorzystywane wyłącznie do sprawdzenia czy nowa wersja jest dostępna. Expo (firma 650 Industries) jest naszym dostawcą usług hostingu — patrz https://expo.dev/privacy.

### 2. Powiadomienia lokalne

Aplikacja wysyła **lokalne powiadomienia** (przypomnienia o wyzwaniu dnia, piciu wody, serii dni). Te powiadomienia są generowane **na samym urządzeniu** — nie są pushami z zewnętrznego serwera, nie wymagają połączenia z internetem.

---

## Zgodność z prawem dotyczącym dzieci

### COPPA (Children's Online Privacy Protection Act, USA)
Aplikacja jest projektowana dla dzieci poniżej 13 roku życia. Zgodnie z COPPA:
- Nie zbieramy danych osobowych dzieci
- Nie wykorzystujemy reklam behawioralnych
- Nie udostępniamy żadnych danych stronom trzecim w celach marketingowych
- Nie integrujemy z usługami social media (brak logowania, brak udostępniania)

### GDPR-K (Europa)
Wszystkie powyższe zasady mają zastosowanie również do użytkowników w Unii Europejskiej.

---

## Twoje prawa

Ponieważ aplikacja nie zbiera danych poza urządzeniem, **wszystkie dane są pod Twoją kontrolą**:
- Aby usunąć dane: użyj funkcji **„Reset postępów"** w ekranie profilu, lub odinstaluj aplikację
- Aby wyeksportować dane: aplikacja nie ma takiej funkcji (dane są tylko lokalne — nie są przechowywane w chmurze)

---

## Zmiany w polityce

Jeśli kiedykolwiek wprowadzimy istotne zmiany w sposobie traktowania danych (np. dodanie konta w chmurze), powiadomimy o tym w wersji aplikacji oraz w polityce. Aktualna wersja zawsze jest dostępna pod adresem podanym w App Store / Google Play.

---

## Kontakt

Pytania dotyczące prywatności lub aplikacji:  
**Artek (Stergo)** — artek29i@gmail.com

---

## English Summary

The application **"Podróż Dookoła Zdrowia"** does not collect, store, or share any personal information from children under the age of 13 (or the relevant minimum age in the applicable jurisdiction). The app operates fully offline and does not transmit any data to third-party servers. All progress is stored locally on the device only.

**Compliance:** COPPA (USA), GDPR-K (EU). No third-party analytics, no advertising SDKs, no in-app purchases, no social media integration.

**Contact:** artek29i@gmail.com

---

*Aplikacja „Podróż Dookoła Zdrowia" jest projektem edukacyjnym pilotażowym. Twórca działa jako osoba fizyczna; aplikacja nie pochodzi od żadnej korporacji ani podmiotu komercyjnego.*
