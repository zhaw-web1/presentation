# Scythe of Seraph

---

## Projekt-Idee

- Neue Website für Scythe of Seraph
- Beinhaltet:
  - Teams
  - News
  - Resultate
  - Infos über Organisation

----

## Sitemap Seite

<img src="./images/sitemap.png"/>

----

## Design

- Mockup mit Invision Studio gemacht
- Breakpoints für Mobile und Desktop

<img src="./images/mockup.png"/>

---

## Technologien

----

### Angular 7

**Komponentensystem**

```html
<app-home></app-home>
```

```
- home/
  - home.component.scss // SCSS stylesheet
  - home.component.html // HTML-Template
  - home.component.ts   // Typescript 'Controller'
```

Notes: Einfache, wiederverwendbare komponenten

----

### Angular - Unsere Erfahrung
- Projektstruktur
- Lazy Loaded Module
- Material CDK: Drag & Drop
- Material CDK: Material-Native Select

Notes: Wir konnten an seperaten Teilen der App arbeiten ohne grosse merge conflicts zu erhalten  
Lazy Loaded Modules führen dazu dass ein normaler Besucher z.B. das Admin Panel nie lädt   -> App wird kleiner

----

#### Firebase - Features
- *Authentication*
- *Database* (Firestore & Realtime DB)
- *Hosting*
- Push Notifications
- Analytics
- Functions

Notes: 
Platform as a Service  
Authentifizierungsanbieter (Google, Github, Email, Passwordless...)  
Functions: cloud scaled node.js API endpunkte

----

#### Firebase - Firestore
- Datenbank
- NoSQL Document Storage
- Real-Time updates mit Websockets

---

## Styling

- CSS Framework: Ja oder nein?
- Layout
- Vorteile von SCSS
- Responsive Design