# NTP — redesign strony

Responsywny projekt strony Network Technologies Polska, przygotowany jako samodzielny plik HTML.

## Wersje online

- [Wersja pełna](https://soninmaster.github.io/ntp-redesign/) — `index.html`.
- [Wersja krótka: one-pager](https://soninmaster.github.io/ntp-redesign/onepager.html) — `onepager.html`: zwięzła oferta, wybrani klienci i kontakt.

Każda wersja zawiera własne style i grafikę SVG. Krótka wersja nie wymaga JavaScriptu.

## Podgląd

Otwórz `index.html` w przeglądarce. Projekt działa offline i nie wymaga instalowania zależności ani procesu budowania.

Opcjonalnie uruchom serwer lokalny:

```sh
python3 -m http.server 8765 --bind 127.0.0.1
```

Następnie otwórz http://127.0.0.1:8765.

## Zawartość

- Układ dostosowany do komputerów i telefonów.
- Wbudowane style CSS, grafika SVG i JavaScript.
- Mobilne menu, rozwijane opisy usług i zakładki z obsługą klawiatury.
- Odnośniki do poczty i telefonu.
- Uwzględnienie preferencji ograniczenia animacji.

Widok aplikacji jest ilustracją koncepcji integracji i zawiera przykładowe dane. Projekt nie łączy się z rzeczywistym systemem CRM ani bazą danych.

Treści firmy opracowano na podstawie ntp.pl. To projekt nowej strony, niezależny od obecnie opublikowanej witryny.
