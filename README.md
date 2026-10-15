# Northline — portfolio demo

Statyczna strona demonstracyjna wykonana w HTML i CSS, przygotowana do publikacji przez GitHub Pages.

> Northline Renovations to fikcyjna firma, a projekt jest demonstracją do portfolio — nie realizacją dla prawdziwego klienta. Formularz kontaktowy jest demonstracyjny i nie wysyła wiadomości.

## Publikacja

1. W repozytorium otwórz **Settings → Pages**.
2. W polu **Build and deployment** ustaw **Source: GitHub Actions**.
3. Otwórz **Actions** i sprawdź, czy workflow zakończył się sukcesem.

Po poprawnym wdrożeniu strona będzie dostępna pod adresem: https://kulik2026.github.io/northline-portfolio/

Workflow GitHub Actions wdraża witrynę po każdym pushu do gałęzi `main`.

## Pliki
- `index.html` — struktura strony
- `style.css` — styl i responsywność
- `.github/workflows/pages.yml` — automatyczne wdrażanie
- `.nojekyll` — wyłącza przetwarzanie Jekyll