# README für Lehrende – Python-Selbstlernkurs Medieninformatik 🧑‍🏫🐍

Dieses Dokument richtet sich an **Lehrende**, die den Python‑Selbstlernkurs im Studiengang
**Medieninformatik** begleiten oder einsetzen möchten.  
Es erklärt Aufbau, Ziele, bewährte Unterrichtsstrategien und Hinweise zur Betreuung.

---

# 🎯 1. Zielsetzung des Kurses

Der Kurs wurde entwickelt, um Studierende im **3. Semester Medieninformatik** auf einen
einheitlichen Python‑Kompetenzstand zu bringen – unabhängig von sehr heterogenen
Vorkenntnissen:

- einige hatten **mehrjährige Python-Erfahrung** (Schule, Projekte),
- andere **ringen noch mit Java**,
- wieder andere haben **Quereinsteigerhintergrund**.

Der Selbstlernkurs ermöglicht:

- individuelles Einstiegstempo  
- adaptive Lernpfade (über den **Einstufungstest**)  
- kontinuierliche Übungsmöglichkeiten  
- klare Struktur (Module + Übungssets)  
- Einsatz in Vorlesungen, Praktika oder Selbstlernphasen  

---

# 🧭 2. Struktur und Materialien

Das Repository enthält:

```
INDEX_overview.ipynb        ← Zentrales Navigations-Notebook
notebooks/                  ← Module 00–07
exercises/                  ← Übungssets A/B/C
placement/                  ← Einstufungstest
docs/                       ← Guides für Lernende & Codespaces-Anleitung
.devcontainer/              ← Vollständig vorkonfigurierte Umgebung
```

## Module (00–07)
Didaktisch aufeinander aufbauend, praxisnah, mit Medieninformatik‑Bezug:
- Basics, Kontrollstrukturen, Funktionen  
- Datenstrukturen (Listen, Dicts), Dateien/CSV  
- Fehlerbehandlung, Debugging  
- Module/Projektstruktur

## Übungssets (Level A, B, C)
Zur Vertiefung oder Differenzierung:

- **A** = Einsteiger  
- **B** = Mittelstufe  
- **C** = Fortgeschritten  

Alle Sets haben klar formulierte Aufgaben inkl. Startercode.

## Einstufungstest
Empfiehlt einen Lernpfad (A/B/C).  
Kann zu Beginn eines Semesters genutzt werden, um Studierende zu sortieren.

---

# 🚀 3. Nutzung im Kurs / mögliche Szenarien

## Szenario A – Selbstlernphase vor Semesterbeginn
- Studierende erhalten Link zum Repo  
- bearbeiten Einstufungstest  
- absolvieren mindestens Modul 00–03  
- Start ins Semester gelingt deutlich homogenisiert

## Szenario B – Flipped Classroom
1. Studierende arbeiten zuhause Module + Übungen durch  
2. Präsenzzeit = Fragen klären, Projekte, Anwendung, Pair‑Programming  
3. Lehrende agieren als Coach statt Inhaltsvermittler

## Szenario C – Integrierter Teil eines Praktikums
- Module 00–07 = Pflicht  
- Übungen B/C = benotete Übungsblätter  
- Codespaces eliminiert Installationsprobleme

## Szenario D – Freies Lernen während Projekten
- Studierende nutzen das Repo als Referenz  
- ideal in Projektkursen, wenn Python nur „Werkzeug“ ist

---

# 🛠️ 4. Hinweise zur Betreuung

## 4.1 Umgang mit heterogenen Gruppen
- Studierende nicht unter Druck setzen, „alle das Gleiche zur gleichen Zeit“ zu leisten  
- Level A/B/C konsequent kommunizieren  
- Fortgeschrittene früh in **Projektrollen** bringen (z. B. Mentoring)

## 4.2 Nutzung von GitHub Codespaces
Empfehlenswert, weil:
- keine Installation nötig  
- einheitliche Umgebung  
- Jupyter läuft stabil  
- Lehrende können Studierenden bei identischen Umgebungen besser helfen  

Hinweis: Einige Studierende brauchen Hilfe bei der Einrichtung → `using_codespaces.md`.

## 4.3 Typische Stolpersteine Studierender
- Python‑Indentation („Warum sagt er 'IndentationError'?“)  
- Mischung Java <→ Python (Typdenken, Semikolons, CamelCase)  
- Verständnis von Listen vs. Dictionaries  
- Schleifenlogik (insbesondere while + Abbruchbedingungen)  
- Umgang mit Dateien auf relativen Pfaden  

Die Module adressieren diese Probleme explizit.

## 4.4 KI‑Unterstützung
Studierende arbeiten im Repo häufig mit integrierten KI‑Assistenten (VS Code Copilot / ChatGPT).
Aus Sicht der Lehre empfehlenswert:

- KI für Fehlersuche einsetzen lassen  
- aber **nicht** zur Generierung ganzer Lösungen → Studierende sollen Code nachvollziehen können  
- Erklärbär‑Funktion ausdrücklich erlauben  
- im Unterricht über Chancen & Risiken reflektieren

---

# 📊 5. Bewertung & Leistungsnachweise

Mögliche Modelle:

### ✔ Modell 1 – Punktesystem
- Module 00–07 = Pflicht  
- Übungen:  
  - A = 1 Punkt pro Aufgabe  
  - B = 2 Punkte  
  - C = 3 Punkte  
- Abschlussprojekt: 40 % der Note  

### ✔ Modell 2 – Kompetenzbasiert
- Studierende demonstrieren praktische Skills (z. B. Daten einlesen, Schleifen, Fehlerbehandlung)  
- Fokus auf **Beherrschen**, nicht auf Anzahl korrekter Aufgaben  

### ✔ Modell 3 – Mini‑Prüfung im Notebook
- kleine Live‑Coding‑Aufgabe  
- fair, da alle mit Jupyter gearbeitet haben  
- KI‑freie Zeit notwendig

---

# 📦 6. Anpassung & Erweiterbarkeit

Der Kurs ist modular und lässt sich leicht erweitern:

- zusätzliche Übungen (z. B. API‑Requests, JSON, Reguläre Ausdrücke)
- ein Projekt „Medienanalyse“ für das Semester  
- automatische Tests mit `pytest`  
- Gamification (Badges für absolvierte Module)  

Die Struktur ist absichtlich offen gehalten.

---

# 🧑‍🏫 7. Tipps für neue Lehrende

- erst **INDEX_overview.ipynb** durchgehen  
- dann Module 00–02 selbst testen  
- anhand von 3–5 Studierenden prüfen, ob Level A/B/C Empfehlungen passen  
- bewusst kurze Theorieeinheiten planen (Python ist Doing-first!)  
- bei Fragen gerne ergänzen: Dieses Repo ist dafür gebaut, mitzuwachsen

---

# 🙌 Viel Erfolg beim Einsatz!

Bei Bedarf kann dieses README erweitert werden, z. B. um Musterklausuren,
Projektaufgaben oder FAQ für Lehrende.

