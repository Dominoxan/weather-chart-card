# Changelog

Wszystkie istotne zmiany w tym forku. Format oparty na [Keep a Changelog](https://keepachangelog.com/pl/1.1.0/),
wersjonowanie zgodne z numeracją tagów upstreamu (`Vx.y.z`).

## [V2.4.13] — 2026-10-18

### Dodane
- Polskie tłumaczenia interfejsu **edytora karty** (74 etykiety): `editorLocale` w `src/locale.js`,
  metody `t()` i `langName()` w `src/weather-chart-card-editor.js`. Inne języki dostają fallback angielski.
- Nazwy języków na liście wyboru generowane przez `Intl.DisplayNames` (w języku interfejsu).

### Zmienione
- Przypięte wersje zależności: `chart.js 4.4.1`, `chartjs-plugin-datalabels 2.2.0`, `lit 2.8.0`,
  `relative-time 1.0.0`, `rollup 4.9.6` oraz override `@kurkle/color 0.3.2`.
  Build odtwarza teraz bundle V2.4.11 bajt w bajt (`sha256 5e632414…2cee92`).
- `package.json`: wersja `2.4.13` (wcześniej nieaktualne `1.0.1`).

### Bez zmian
- Kod karty (`src/main.js`) i jej zachowanie — zmiany dotyczą wyłącznie edytora i builda.

## [V2.4.12] — 2026-10-18

### Zmienione
- Repozytorium przejęte po `mlamberts78/weather-chart-card` (upstream oznaczony jako nieutrzymywany).
- `package-lock.json` dodany do repo (usunięty z `.gitignore`) — warunek odtwarzalnych buildów.

### Bez zmian
- Bundle `weather-chart-card.js` identyczny z V2.4.11.
