# FixIt – Reparatur-Wiki für Elektrogeräte

FixIt ist eine moderne Webanwendung zur Darstellung von Reparaturanleitungen für Elektrogeräte mithilfe der iFixit API.
Ziel ist es, Elektroschrott zu reduzieren und nachhaltiges Verhalten zu fördern, indem Nutzern einfach zugängliches Reparaturwissen bereitgestellt wird.

---

## Features

* Suche nach Elektrogeräten
* Anzeige von Reparaturanleitungen
* Schritt-für-Schritt Anleitungen
* Integration der iFixit API
* Schnelle Weboberfläche mit Vite

---

## Motivation

Viele Elektrogeräte werden entsorgt, obwohl sie noch reparierbar sind.
FixIt hilft dabei, Reparaturen zugänglich zu machen und dadurch Müll zu reduzieren.

---

## Technologien

* HTML
* CSS
* JavaScript / TypeScript
* Node.js
* npm
* Vite
* iFixit API

---

## Projektstruktur

```id="5kj9y6"
FixIt/
│── public/
│── src/
│── index.html
│── package.json
│── package-lock.json
│── vite.config.ts
│── tsconfig.json
│── tsconfig.app.json
│── tsconfig.node.json
│── eslint.config.js
│── .gitignore
│── README.md
```

---

## Installation

### 1. Node.js installieren

Download: https://nodejs.org
Empfohlen: **LTS Version**

---

### 2. Installation überprüfen

```id="9q2j8w"
node -v
npm -v
```

---

### 3. Repository klonen

```id="d5y8g2"
git clone https://github.com/duck343/Fixit.git
cd Fixit
```

---

### 4. Abhängigkeiten installieren

```id="x6n4k1"
npm install
```

---

### 5. Projekt starten

```id="6w2k9z"
npm run dev
```

Danach im Browser öffnen:
http://localhost:5173

---

## API Nutzung

Dieses Projekt verwendet die iFixit API zur Abfrage von Reparaturanleitungen.

Basis URL:

```id="r4c8h1"
https://www.ifixit.com/api/2.0/
```

---

## Workflow

1. Nutzer sucht nach einem Gerät
2. Anfrage wird an die API gesendet
3. Daten werden verarbeitet
4. Anleitung wird angezeigt

---

## Zukünftige Features

* Benutzerkonten
* Favoriten speichern
* Eigene Anleitungen hinzufügen
* Bewertungen und Kommentare

---

## Team

* Ekin Yarar
* Daniel

HTL Spengergasse Wien
Klasse: 3CHIF

---

## Thema

Umwelt & Nachhaltigkeit
