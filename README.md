# libft - README

![libft](https://github.com/byaliego/42-project-badges/blob/main/badges/libftm.png?raw=true)

## Überblick

Dieses Repository enthält die Implementierung einer grundlegenden C-Bibliothek, libft, im Rahmen des 42-Programmierkurses. Die Bibliothek umfasst Funktionen, die in späteren Projekten als Hilfsmittel dienen sollen. Die README bietet eine Übersicht über die Struktur, Funktionen und technischen Aspekte der Bibliothek.

## Verzeichnisstruktur

- `Makefile`: Enthält Regeln für die Kompilierung und Bereitstellung der Bibliothek.
- `libft.h`: Header-Datei mit Funktionssignaturen und einer Struktur für Listen.
- `ft_*.c`: Implementierungen der geforderten Funktionen.

## Makefile-Regeln

- `NAME`: libft.a
- `all`: Kompiliert die gesamte Bibliothek.
- `clean`: Entfernt temporäre Dateien.
- `fclean`: Entfernt erstellte Dateien und die Bibliothek.
- `re`: Entfernt alle Dateien und erstellt die Bibliothek neu.

## Geforderte Funktionen

Die Bibliothek implementiert grundlegende Funktionen, einschließlich Manipulation von Zeichenketten, Zeichenprüfungen und Speichermanipulation.

## Bonus-Teil

Zusätzlich zur Pflichtimplementierung enthält die Bibliothek Funktionen zur Manipulation von Listen.

## Verwendung

Projekte können diese Bibliothek als Submodul einbinden und `libft.h` in ihren Quellcode inkludieren, um die Funktionen zu nutzen.

## Technische Überlegungen

- Keine globalen Variablen.
- Verwendung von statischen Funktionen für Hilfsfunktionen.
- Strikte Einhaltung von Kompilierungsflags (-Wall -Wextra -Werror).
- Verbot von libtool, Verwendung von `ar` zur Bibliothekenerstellung.
