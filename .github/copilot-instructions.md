# Copilot Instructions – PinpointIT Astro Landing Page

## Projektkontext
Dieses Repository enthält die neue statische Landing Page von **PinpointIT**.

PinpointIT ist ein technologiegetriebenes Beratungsunternehmen mit Fokus auf:
- KI-Beratung
- Automatisierung & datengetriebene Entscheidungsfindung
- quantitative / algorithmische Systeme (z. B. Trading, Optimierung)

Die bestehende WordPress-Webseite (www.pinpointit.de) dient **nur als historischer Ausgangspunkt**.
Inhalte, Struktur, Wortwahl und Design dürfen und sollen **grundlegend modernisiert oder vollständig ersetzt** werden.

## Ziel der Website
- One‑Page oder sehr schlanke Multi‑Page Landing Page
- keine Benutzerkonten
- kein Backend
- keine Form-Logik (Kontakt via Mailto oder externem Tool)
- statisch generiert und kostenlos auf GitHub Pages gehostet

Primäres Ziel:
> Kompetenz, Präzision und technologische Tiefe vermitteln – nicht Marketing-Lautstärke.

## Technologischer Rahmen
- Framework: Astro
- Basis: AstroWind (stark reduziert & angepasst)
- Styling: Tailwind CSS
- Deployment: GitHub Pages (static build)
- JavaScript: so wenig wie möglich
- Performance & Lighthouse Scores haben Priorität

Keine Vorschläge für:
- WordPress
- klassische CMS-Systeme
- Datenbanken
- Server, APIs oder Authentifizierung

## Design- & UX-Prinzipien
- modern, ruhig, selbstbewusst
- eher dunkel (Dark Mode-first)
- viel Weißraum
- klare Typografie
- keine Stockfotos von Menschen
- abstrakte Visuals, Shapes, Linien oder Daten-Metaphern sind erlaubt

Animationen:
- nur dezent (Fade, Slide, Scroll-Reveal)
- niemals auf Kosten von Performance

## Inhaltliche Leitlinien
Bitte vermeiden:
- generische Marketingphrasen
- Buzzwords ohne Substanz
- „Wir sind innovativ“-Aussagen

Bevorzugt:
- kurze, präzise Aussagen
- technisch glaubwürdige Sprache
- Fokus auf Ergebnisse, Systeme und Entscheidungsqualität

Beispielhafte Tonalität:
- „Wir bauen Systeme, die Entscheidungen treffen.“
- „Von Strategie bis zum produktiven Einsatz von künstlicher Intelligenz.“
- „Messbar. Reproduzierbar. Automatisiert.“

## Struktur-Empfehlung
- Hero Section mit klarer Positionierung
- 3 Kernleistungen (KI-Beratung, Automatisierung, Quantitative Systeme)
- Warum PinpointIT (Engineering-Fokus, Tiefe, Erfahrung)
- Zukunfts- & KI-Fokus
- Klarer Call-to-Action

## Code-Stil
- saubere, kleine Astro-Komponenten
- sprechende Dateinamen
- keine überabstrakten Patterns
- lieber explizit als „clever“

Kommentare:
- nur dort, wo Architekturentscheidungen erklärt werden müssen

## Erwartung an Copilot
Copilot soll:
- Vorschläge machen, die zu einer statischen Astro-Landing-Page passen
- bestehende Inhalte kritisch hinterfragen
- lieber vereinfachen als verkomplizieren
- Design- & Textvorschläge liefern, die technologische Kompetenz ausstrahlen

Copilot soll **nicht**:
- alte Inhalte ungeprüft übernehmen
- Marketing-Texte aufblasen
- unnötige Features erfinden
