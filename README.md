# template-static-page-deploy

Um den Inhalt des Ordners "public" nach jedem Commit automatisch als statische Webseite über GitHub Pages zu veröffentlichen, gehen Sie bitte wie folgt vor:

1. Wählen Sie unter ["Settings / Pages"](../../settings/pages) bei "Build and Deployment" als "Source" den Eintrag "GitHub Actions".
2. Bennenen Sie in Ihrem Repository die Datei `.github/workflows/static.yml.disabled` um in `.github/workflows/static.yml` (das `.disabled` aus dem Dateinamen löschen)
3. Committen Sie die Datei. Nach kurzer Zeit können Sie die unter ["Settings / Pages"](../../settings/pages) veröffentlichte URL der GitHub Page besuchen und sehen dort den Inhalt des Ordners public.


Pages-URL
https://htwg-in-schneider.github.io/frontend-static-plantable/index.html
