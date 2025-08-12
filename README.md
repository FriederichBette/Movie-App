# Movie Collection CLI

Ein einfaches Python-Programm, um Filme in einer Liste zu verwalten.  
Es ermöglicht das Hinzufügen neuer Filme, das Anzeigen aller gespeicherten Filme sowie die Suche nach einem bestimmten Titel.

## Funktionen

- **Film hinzufügen**: Titel, Regisseur und Erscheinungsjahr eingeben
- **Filmliste anzeigen**: Zeigt alle gespeicherten Filme in der Konsole an
- **Film suchen**: Sucht in der Liste nach einem exakten Titel
- **Programm beenden**: Über das Menü beenden

## Installation

1. Sicherstellen, dass Python 3 installiert ist:
   ```bash
   python --version
   ```
2. Diese Datei herunterladen und z. B. als `movies.py` speichern.
3. Das Programm starten:
   ```bash
   python movies.py
   ```

## Bedienung

Nach dem Start erscheint folgendes Menü:

```
Enter 'a' to add a movie, 'l' to see your movies, 'f' to find a movie by title, or 'q' to quit:
```

- `a` → Film hinzufügen  
- `l` → Liste aller Filme anzeigen  
- `f` → Film anhand des Titels suchen (Groß-/Kleinschreibung wird ignoriert)  
- `q` → Programm beenden  

## Beispiel

```
Enter 'a' to add a movie, 'l' to see your movies, 'f' to find a movie by title, or 'q' to quit: a
Enter the movie title: Inception
Enter the movie director: Christopher Nolan
Enter the movie release year: 2010

Enter 'a' to add a movie, 'l' to see your movies, 'f' to find a movie by title, or 'q' to quit: l
Title: Inception
Director: Christopher Nolan
Year: 2010
```

## Hinweise

- Die Daten werden nur im Arbeitsspeicher gehalten und gehen nach dem Beenden verloren.
- Die Suche nach Filmen erfordert eine exakte Übereinstimmung des Titels, ignoriert jedoch die Groß- und Kleinschreibung.
