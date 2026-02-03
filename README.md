# 🎪 Rodzinne Wydarzenia — Poznań

Dashboard prezentujący wydarzenia kulturalne dla rodzin z dziećmi w Poznaniu.

## 🌐 Live Demo

**https://ludwiczakpawel.github.io/rodzinne-wydarzenia-poznan/**

## ✨ Funkcje

- **📅 Wydarzenia podzielone na sekcje:**
  - Ten weekend (sobota i niedziela)
  - Ten tydzień (kolejne 7 dni)
  - Nadchodzące (następne 3-4 tygodnie)

- **🎯 Filtry kategorii:**
  - 🎬 Kino
  - 🎭 Teatr
  - 🎵 Muzyka/Koncerty
  - 🌳 Wydarzenia plenerowe
  - 🎨 Warsztaty
  - 📅 Inne

- **📱 Responsywny design** - działa świetnie na telefonach i tabletach
- **🌙 Ciemny motyw** - przyjemny dla oczu
- **⚡ Szybki i lekki** - statyczna strona, ładuje się natychmiast

## 🔄 Aktualizacja danych

Dashboard automatycznie aktualizuje się danymi z pliku `events.json`. 

Dane są zbierane automatycznie ze źródeł:
- poznan.pl (kalendarz wydarzeń)
- kinoapollo.pl
- cortique.pl
- ...i innych

## 🛠️ Technologia

- Czysty HTML, CSS i JavaScript (zero zależności!)
- Hostowane na GitHub Pages
- Dane w formacie JSON

## 📝 Źródło danych

Plik `events.json` zawiera strukturę:

```json
{
  "last_updated": "2026-02-03T08:28:11.751887Z",
  "events": [
    {
      "title": "Nazwa wydarzenia",
      "venue": "Miejsce",
      "date": "2026-02-03",
      "time": "16:30",
      "category": "theater",
      "age_range": [3, 10],
      "description": "Opis...",
      "url": "https://...",
      "tags": ["weekend", "theater"]
    }
  ]
}
```

## 🚀 Rozwój

Projekt jest częścią systemu automatycznego zbierania wydarzeń rodzinnych w Poznaniu.

---

Made with ❤️ for families in Poznań
