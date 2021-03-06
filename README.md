# Willkommen im Repository des Buches "GitHub – Eine praktische Einführung"

<a href="https://oreilly.de/produkt/github-eine-praktische-einfuehrung/"><img align="left" width="200" height="291" src="https://githubbuch.github.io/assets/images/Buchcover_200.jpg" style="float:left; padding-right:10px" alt="Buchcover"></a>

Du wirst hier folgende Sachen finden:

* Die Linksammlung zum Buch
* Eine Referenz, wie man aus einem Repository mittels GitHub Pages eine Website generiert (Kapitel 10)
* Den Quellcode aus Kapitel 9 ("Der GitHub Marketplace – Actions und Apps")

## Linksammlung zum Buch

Die Linksammlung des Buches findest du entweder bei den Dateien nach dem Muster *CHXX.md* (*XX* steht dabei für die Kapitelzahl) oder du gehst auf die eigens dafür erstellte [Website](https://githubbuch.github.io).

<br>

## Referenz für GitHub Pages

Schau dir folgende Dateien an:

### Struktur
* Die Navigationsdatei: [/_includes/nav.html](/_includes/nav.html)
* Die um die Navigation ergänzte Layout-Seite: [/_layouts/default.html](/_layouts/default.html)
* Anpassungen des Farbschemas: [/assets/css/style.scss](/assets/css/style.scss)
* Die globale Konfigurationsdatei der Website [_config.yml](_config.yml)

### Inhalte
* Die Startseite der Website [index.md](index.md)
* Die einzelnen Seiten der Website nach dem Muster *CHXX.md* (*XX* steht dabei für die Kapitelzahl), bspw. [CH00.md](CH00.md)
* Die individuelle Fehlerseite [404.md](404.md)

## Quellcode zum Buch

Im Buch zeige ich, wie man eine eigene Action bauen kann, die neue Issues automatisch mit einem bestimmten Label versieht. Der Quellcode dafür ist hier zu finden:

* Workflow-Datei: [.github/workflows/issuelabeler.yml](.github/workflows/issuelabeler.yml)
* Action-Datei: [.github/actions/issuelabeler/action.yml](.github/actions/issuelabeler/action.yml)
* JavaScript-Datei: [.github/actions/issuelabeler/index.js](.github/actions/issuelabeler/index.js)
