# FixIt – Reparatur-Wiki für Elektrogeräte

FixIt ist eine Webanwendung zur Darstellung von Reparaturanleitungen für Elektrogeräte über die iFixit API.
Ziel ist es, Elektroschrott zu reduzieren und nachhaltiges Verhalten zu fördern.

## Features

* Suche nach Elektrogeräten
* Anzeige von Reparaturanleitungen
* Schritt-für-Schritt Guides
* API-Anbindung (iFixit)
* Einfache Benutzeroberfläche

## Motivation

Viele Geräte werden weggeworfen, obwohl sie reparierbar sind.
FixIt hilft dabei, Geräte selbst zu reparieren und Müll zu vermeiden.

## Technologien

* HTML
* CSS
* JavaScript
* Node.js
* npm
* Vite
* iFixit API

## Projektstruktur

```
FixIt/
│── index.html
│── package.json
│── vite.config.js
│── src/
│   │── main.js
│   │── app.js
│   │── components/
│   │   │── search.js
│   │   │── guide.js
│   │── services/
│   │   │── api.js
│   │── styles/
│   │   │── style.css
│── public/
│   │── images/
│── README.md
```

## Installation

### 1. Node.js installieren

https://nodejs.org (LTS Version)

### 2. Installation überprüfen

```
node -v
npm -v
```

### 3. Repository klonen

```
git clone https://github.com/duck343/Fixit.git
cd Fixit
```

### 4. Abhängigkeiten installieren

```
npm install
```

### 5. Projekt starten

```
npm run dev
```

Browser öffnen:
http://localhost:5173

## API Nutzung

Basis URL:

```
https://www.ifixit.com/api/2.0/
```

## Workflow

1. Nutzer sucht nach einem Gerät
2. Anfrage an API
3. Daten werden verarbeitet
4. Anleitung wird angezeigt

## Zukünftige Features

* Benutzerkonten
* Favoriten speichern
* Eigene Guides hinzufügen
* Bewertungen

## Team

* Ekin Yarar
* Daniel

HTL Spengergasse Wien
Klasse: 3CHIF

## Thema

Umwelt & Nachhaltigkeit
