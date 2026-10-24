# Chess.ai — oficjalne instalatory

[Strona i pobieranie](https://chess-ai.tota-tomasz13.workers.dev) · [Najnowsze wydanie](https://github.com/totatomasz13-web/chess-ai-releases/releases/latest)

Windows 10/11 x64 oraz Android APK. Aplikacja internetowa i Android PWA są dostępne na stronie.

## Licencja

Oprogramowanie własnościowe. © 2026 autor projektu Chess.ai (totatomasz13-web). Wszelkie prawa zastrzeżone.

Nie kopiuj ani nie rozpowszechniaj instalatorów na innych stronach. Udostępniaj link do oficjalnej strony. Dozwolone jest pobranie, instalacja i używanie aplikacji oraz własna kopia zapasowa zgodnie z [LICENSE.txt](LICENSE.txt). Biblioteki osób trzecich zachowują własne licencje. Własne modele i dane użytkownika pozostają jego własnością.

Kod źródłowy znajduje się w osobnym prywatnym repozytorium. To repozytorium zawiera wyłącznie informacje, licencję i pliki wydań.

## Aktualizacje

- Windows pobiera aktualizacje w tle i instaluje po zamknięciu aplikacji.
- Android sprawdza nowe wydania; instalację pobranego APK potwierdzasz w systemie. Zachowaj zainstalowaną aplikację, aby aktualizacja zachowała lokalne modele.
- Aktualizacje nie usuwają modeli. Zalecany jest regularny eksport wag do własnej kopii.

## Trening

CPU w JavaScript działa na wszystkich platformach. Wersja Windows obsługuje Python/PyTorch na CPU oraz GPU NVIDIA/CUDA po zainstalowaniu środowiska Python. Samogranie i reguły szachów działają na CPU; GPU może aktualizować wagi sieci.

Pierwsze wydania Windows nie mają certyfikatu podpisu cyfrowego. Android APK jest podpisywany stałym kluczem projektu.
