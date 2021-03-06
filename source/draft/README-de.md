Draft 0.8.11
============
Unterstützung für Entwurfsseiten.

<p align="center"><img src="draft-screenshot.png?raw=true" width="795" height="836" alt="Bildschirmfoto"></p>

## Wie man eine Entwurfsseite macht

Ganz oben auf einer Seite kannst du `Status: draft` in den [Einstellungen](https://github.com/datenstrom/yellow-extensions/tree/master/source/core/README-de.md#einstellungen) festlegen. Die Seite ist dann nicht mehr sichtbar. Du kannst die Seite weiterhin im [Webbrowser](https://github.com/datenstrom/yellow-extensions/tree/master/source/edit/README-de.md) und im Dateisystem bearbeiten.

## Wie man Entwurfsseiten wiederfindet

Alle Entwurfsseiten sind auf deiner Webseite vorhanden als `http://website/edit/drafts/`. Du kannst auch die [Search-Erweiterungen](https://github.com/datenstrom/yellow-extensions/tree/master/source/search/README-de.md) benutzen. Sobald du mit deinem Benutzerkonto angemeldet bist, kannst du nach `status: draft` suchen. Auf diese Weise kannst du alle Entwurfsseiten wiederfinden.

## Beispiele

Inhaltsdatei mit Draft-Status:

    ---
    Title: Beispielseite
    Status: draft
    ---
    Das ist eine Beispielseite.

Inhaltsdatei mit Draft-Status fürs Blog:

    ---
    Title: Blogseite
    Published: 2013-04-07
    Author: Datenstrom
    Layout: blog
    Tag: Beispiel
    Status: draft
    ---
    Das ist eine Beispiel-Blogseite.
 
Inhaltsdatei mit Draft-Status fürs Wiki:

    ---
    Title: Wikiseite
    Layout: wiki
    Tag: Beispiel
    Status: draft
    ---
    Das ist eine Beispiel-Wikiseite.

## Einstellungen

Die folgenden Einstellungen können in der Datei `system/extensions/yellow-system.ini` vorgenommen werden:

`DraftPaginationLimit` = Anzahl der Einträge pro Seite  

Die folgenden Dateien können angepasst werden:

`system/layouts/draftpages.html` = Layoutdatei mit Übersicht der Entwurfsseiten  

## Installation

[Erweiterung herunterladen](https://github.com/datenstrom/yellow-extensions/raw/master/zip/draft.zip) und die Zip-Datei in dein `system/extensions`-Verzeichnis kopieren. Rechtsklick bei Safari.

## Entwickler

Datenstrom. [Hilfe finden](https://datenstrom.se/de/yellow/help/).

<p>
<a href="README-de.md"><img src="https://raw.githubusercontent.com/datenstrom/yellow-extensions/master/source/help/language-de.png" width="15" height="15" alt="Deutsch">&nbsp; Deutsch</a>&nbsp;
<a href="README.md"><img src="https://raw.githubusercontent.com/datenstrom/yellow-extensions/master/source/help/language-en.png" width="15" height="15" alt="English">&nbsp; English</a>&nbsp;
</p>
