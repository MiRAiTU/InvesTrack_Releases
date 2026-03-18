## Wersja 1.2.1 — Poprawki Wizualne i Automatyczny Build

Data wydania: 18 marca 2026

---

### 🐛 Poprawki Błędów
- **Przezroczyste dropdowny** — naprawiono problem z przezroczystym tłem list rozwijanych (`QComboBox`) na Windows; dodano `combobox-popup: 0` wymuszające własny renderer Qt zamiast systemowego

### ⚙️ Infrastruktura
- **GitHub Actions** — dodano workflow automatycznie budujący `MiRAiSetup_1.2.1.exe` na środowisku Windows przy każdym pushu do `master`; plik instalatora dostępny jako artefakt do pobrania bezpośrednio z zakładki Actions

## v1.1.2 — 2026-03-18

  ### Zmiany
  - Przeniesienie repozytorium aktualizacji do publicznego repozytorium `MiRAiTU/InvesTrack_Releases`
  - Aktualizacje nie wymagają już tokenu GitHub — aplikacja sprawdza nowe wersje bez konieczności konfiguracji tokenu
  - Poprawiono komunikat błędu pobierania — nie sugeruje już problemów z autoryzacją gdy repozytorium jest publiczne
