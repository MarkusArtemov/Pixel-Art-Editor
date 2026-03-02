# Pixel Art Editor

Webbasierter 2D-Sprite- und Tilemap-Editor, entwickelt im Rahmen eines Hochschulprojekts (WS 2024/25, Hochschule Flensburg).  
Umgesetzt als Single-Page-Application ohne Einsatz eines Frontend-Frameworks.


## Funktionen

### SpriteEditor

- Pixelbasiertes Zeichnen mit der HTML5 Canvas API  
- Mehrere Frames zur Animationserstellung  
- Onion-Skin-Unterstützung  
- Selektions- und Shape-Tools  
- Spiegeln von Zeichenoperationen  
- Bresenham-Algorithmus für lückenfreie Linien  
- Zoom und resizable Canvas  

### MapEditor

- Tile-basierte Kartenstruktur  
- Layer-Management (Reihenfolge, Sichtbarkeit, Entfernen)  
- Selection- und Shape-Tools  
- Karten-Vorschau  

### FileArea

- Ordnerbasierte Projektstruktur  
- CRUD-Funktionalität für Sprite- und Map-Dateien  
- Drag-and-Drop-Organisation  


## Architektur

Frontend (Vanilla JavaScript, CustomElements, Canvas API)  
⇄ REST (HTTP/JSON)  
Backend (Node.js, Express, Sequelize ORM, SQLite)


## Setup

**Voraussetzung:** Node.js 18+

```bash
cd backend
npm install
node server.js
```

Das Frontend aus `frontend/EditorTool` mit einem lokalen Entwicklungsserver starten.  
Frontend und Backend müssen auf unterschiedlichen Ports laufen.

---

## Autoren

- Markus Artemov  
- Matz Schultz  
- Onur Ulusoy  
