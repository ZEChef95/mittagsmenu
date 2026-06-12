# Mittagsmenü Übersicht

## Beschreibung

Dieses Projekt stellt eine einfache, moderne HTML-Seite bereit, die als zentrale Übersicht für Mittagsmenüs verschiedener Restaurants und Gastronomiebetriebe dient.

Die Anwendung:

- zeigt eine Sammlung von Mittagsmenü-Links an
- berechnet automatisch die aktuelle Kalenderwoche
- enthält einen Dark- und Light-Mode
- verwendet Favicons zur besseren Wiedererkennung der Restaurants
- bietet direkten Zugriff auf externe Menüseiten sowie lokale PDF-Dokumente
- funktioniert vollständig ohne Backend

## Projektstruktur

```text
mittagsmenu-main/
├── mittagsmenues.html      # Hauptanwendung
├── favicon/
│   ├── besteck.png
│   ├── cafeD.jpg
│   └── koi.png
└── pdf/
    └── koi.pdf
```

## Verwendete Technologien

- HTML5
- CSS3
- Vanilla JavaScript
- Google Fonts (Inter)

## Funktionen

### Kalenderwochen-Anzeige
Die aktuelle Kalenderwoche wird automatisch ermittelt und innerhalb der Oberfläche angezeigt.

### Theme-Umschaltung
Benutzer können zwischen Dark Mode und Light Mode wechseln.

### Restaurant-Links
Die Seite enthält Verlinkungen zu verschiedenen Restaurants und Mittagsmenü-Angeboten in der Umgebung von Bludenz.

## Anpassungen

Neue Restaurants können im JavaScript-Bereich der Datei `mittagsmenues.html` ergänzt werden.

Beispiel:

```javascript
{
  label: "Neues Restaurant",
  url: "https://example.com/mittagsmenue",
  favicon: "https://example.com/favicon.ico"
}
```

## Lizenz

Dieses Projekt ist für den privaten bzw. internen Gebrauch vorgesehen. Die Rechte an den verlinkten Mittagsmenüs und Logos liegen bei den jeweiligen Betreibern.
