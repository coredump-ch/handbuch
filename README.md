# Coredump Handbuch

Rendered: <https://coredump-ch.github.io/handbuch/>

## Building

Voraussetzung: Rust und Cargo müssen installiert sein.

Danach:

    cargo install --locked mdbook mdbook-admonish mdbook-toc

Um die Dokumentation zu builden:

    mdbook build

Die HTML-Daten befinden sich im Ordner `book`.

Um einen Entwicklungsserver zu starten:

    mdbook serve

Der Server ist im Browser unter <http://localhost:3000/> erreichbar.
