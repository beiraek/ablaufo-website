# ablaufo — Brand-Template

Referenz für Website, Logo, Visitenkarte, Angebots-PDF. Alles aus einer Quelle, damit die
Marke überall konsistent wirkt.

## Positionierung
- **Was:** Automatisierung wiederkehrender Abläufe (Belegeingang, Nachfassen, Onboarding)
- **Für wen:** Steuerkanzleien (scharfer Fokus)
- **Wo:** Regensburg & Oberpfalz
- **Tonalität:** seriös, ruhig, kompetent. Kein KI-Hype, kein Startup-Bunt.
- **Burggraben:** Datenschutz (EU-Hosting, AVV, Verschwiegenheit) als Verkaufsargument #1.

## Farbpalette (Swiss Clean — ein Akzent)
| Token | Hex | Verwendung |
|---|---|---|
| Ink | `#0E1217` | Headlines, primärer Text |
| Ink-2 | `#3A424E` | Fließtext |
| Muted | `#6B7280` | Captions, Sekundärinfo |
| Line | `#E8EAEE` | Rahmen, Trennlinien |
| Surface | `#F6F7F9` | dezente Sektionsflächen |
| Background | `#FFFFFF` | Grundfläche |
| **Brand** | **`#2456FF`** | **Der eine Akzent: CTA, Links, Icons** |
| Brand-Ink | `#1B3FBF` | Hover/aktiv |
| Brand-Tint | `#EEF2FF` | Icon-Kacheln, weiche Flächen |

**Regel:** Akzent sparsam. Buttons, Links, ein Icon-Akzent, eine Headline-Betonung.
Sonst nur Schwarz/Weiß/Grau. Das ist „clean".

## Typografie — Inter
- Eine Schrift für alles: **Inter** (selbst gehostet als woff2, kein externer Request).
- Gewichte: 400 (Text), 600 (Subheads/Buttons/Eyebrow), 700 (Headlines).
- Headlines: enges Tracking (−0.02 bis −0.03em), Zeilenhöhe ~1.06–1.12.
- Eyebrow-Label: 0.8rem, 600, UPPERCASE, Tracking 0.12em, in Brand-Farbe.

## Wortmarke
- „ablaufo", komplett klein, Inter 700, Tracking −0.02em.
- Akzent: kleiner Brand-farbener Punkt (`#2456FF`) rechts unten am Wort (steht für den
  „Ablauf"/Abschluss eines Prozesses). Schutzraum = Höhe des „a" rundherum.

## Logo-Ideen (für Generierung)
- **Wortmarke + Punkt** (bereits umgesetzt) — sicherste, cleanste Variante.
- **Bildmarke optional:** ein Loop-/Pfeil-Kreis (wiederkehrender Ablauf) oder ein
  stilisiertes „a" mit Bogen. Einfarbig `#2456FF` auf Weiß, bzw. Weiß auf `#0E1217`.
- Favicon: weißes „a" auf `#2456FF`, Radius 14/64.

## Form-Sprache
- Radien: 8px (Buttons), 14px (Karten), 20px (große Flächen), Punkte/Pills rund.
- Schatten dezent, eine Elevations-Stufe + eine stärkere für Hover.
- Viel Weißraum, Section-Padding `clamp(5rem,10vw,8rem)`, Container max 1080px.
- Symmetrie: zentrierte Sektions-Header, gleich hohe Karten, gleicher vertikaler Rhythmus.

## Bausteine (Website)
Sticky-Header · Hero mit Ablauf-Diagramm · Trust-Strip · 3 Leistungs-Karten ·
3-Schritte-Ablauf · Warum-Block · FAQ (mit FAQPage-Schema) · Kontakt-CTA · Footer.
