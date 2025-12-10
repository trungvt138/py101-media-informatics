# Python Selbstlernkurs – Medieninformatik

Wie sehe ich diese Datei in VS Code als Markdown an?
* Drücke Ctrl + Shift + V (Windows/Linux)
* oder Cmd + Shift + V (macOS)
Es öffnet sich ein „Preview“-Fenster rechts.


Willkommen im Selbstlernkurs für Python im 3. Semester Medieninformatik.  
Dieses Projekt unterstützt dich dabei,

- einen **Einstufungstest** zu absolvieren,
- anschließend einen **passenden Lernpfad (Level A/B/C)** zu wählen,
- und alle Inhalte in **VS Code mit Jupyter-Notebooks** Schritt für Schritt zu bearbeiten.

Der Kurs ist bewusst so gestaltet, dass du möglichst schnell produktiv werden kannst – egal ob du viel, wenig oder gar keine Python-Erfahrung hast.

---

## 1. Nutzungsmöglichkeiten

Es gibt zwei empfohlene Wege, wie du mit diesem Kurs arbeiten kannst:

### Variante 1 – Nutzung in der Cloud (empfohlen)
(z. B. GitHub Codespaces, Gitpod oder andere VS-Code-kompatible Cloud-Container)

Diese Variante hat keinen Installationsaufwand und sorgt dafür, dass alle Studierenden in derselben Umgebung arbeiten.

### Variante 2 – Lokale Nutzung
(klassisch mit installiertem Python + lokalem Jupyter in VS Code)

Diese Variante eignet sich, wenn du lieber ohne Cloud arbeitest.

Eine dritte Variante – ein lokaler Dev-Container mit Docker – ist optional für fortgeschrittene Nutzer:innen, aber für diesen Kurs nicht notwendig.

---

## 2. Variante 1 – Arbeiten in der Cloud (empfohlen)

1. Öffne dieses Repository in einem unterstützten Cloud-Dienst  
   (z. B. GitHub Codespaces oder Gitpod).

2. Der Editor startet automatisch in einer vollständig eingerichteten Entwicklungsumgebung  
   inklusive Python, Jupyter und allen benötigten Paketen.

3. Stelle sicher, dass in VS Code die Extensions **Python** und **Jupyter** aktiv sind.

4. Starte mit dem Einstufungstest:

   Öffne:  
   `placement/placement_test.ipynb`

   Führe alle Zellen aus und folge am Ende der Empfehlung für dein **Level (A/B/C)**.

5. Bearbeite danach:

   - die passenden Modul-Notebooks im Ordner `notebooks/`
   - die dazugehörigen Übungen im Ordner `exercises/level_A`, `level_B` oder `level_C`

---

## 3. Variante 2 – Lokale Nutzung ohne Dev-Container

Falls du lieber alles lokal auf deinem Rechner laufen lässt:

1. Installiere **VS Code** und die Erweiterungen:
   - Python
   - Jupyter

2. Klone dieses Repository:

   ```bash
   git clone <URL-zu-diesem-Repo>
   cd python-selfstudy-medieninformatik
   ```

3. Erstelle ein virtuelles Environment und installiere die Abhängigkeiten:

   ```bash
   python -m venv .venv
   # Aktivieren (Linux/macOS)
   source .venv/bin/activate
   # Aktivieren (Windows)
   # .venv\Scripts\activate
   pip install -r requirements.txt
   ```

4. Öffne das Projekt in VS Code und wähle den Python-Interpreter aus `.venv`.

5. Öffne `placement/placement_test.ipynb` und führe die Zellen mit dem ausgewählten Kernel aus.

---

## 4. Variante 3 – Lokaler Dev-Container (optional)

Wenn du bereits Erfahrung mit Docker hast:

1. Stelle sicher, dass Docker Desktop installiert und gestartet ist.
2. Öffne das Projekt in VS Code.
3. Wähle „Reopen in Container“, falls eine `.devcontainer`-Konfiguration vorhanden ist.

Diese Variante stellt ebenfalls eine einheitliche Umgebung bereit, ist aber kein Pflichtbestandteil dieses Kurses.

---

## 5. Lernreihenfolge

1. **Einstieg:**  
   Öffne `placement/placement_test.ipynb` und führe alle Zellen aus.  
   Am Ende bekommst du eine Empfehlung:

   - Level A – Einstieg für Anfänger:innen  
   - Level B – Weiterarbeit für Studierende mit Grundkenntnissen  
   - Level C – Vertiefung für Fortgeschrittene

2. **Danach – je nach Level:**  
   Bearbeite die Modul-Notebooks im Ordner `notebooks/`, z. B.:

   - `00_java_to_python.ipynb`  
   - `01_basics.ipynb`  
   - `02_control_flow.ipynb`  
   - `03_functions.ipynb`  

3. Bearbeite die entsprechenden Übungen unter:

   - `exercises/level_A/`  
   - `exercises/level_B/`  
   - `exercises/level_C/`

4. Am Ende folgt ein kleines Abschlussprojekt im Notebook  
   `notebooks/08_project.ipynb`.

---

## 6. KI-Tutor (Erklärbär)

Du kannst in VS Code jede KI-Chat-Erweiterung nutzen (z. B. GitHub Copilot Chat oder eine andere Chat-Extension).  
Die KI unterstützt dich beim Verstehen, Erklären und Debuggen von Code.

Beispiele für sinnvolle Prompts:

- „Erklär mir bitte den Fehler `TypeError: ...` aus meiner letzten Zelle.“  
- „Erklär meinen Code in einfachen Worten.“  
- „Gib mir einen Hinweis zur Lösung, aber keine komplette fertige Lösung.“

Wichtige Regel:

**Nutze die KI als Erklärbär – nicht als Ersatz für eigenes Denken.**  
Code, den du nicht verstehst, gilt als nicht gelöst.

Weitere Hinweise findest du in `docs/guide_for_students.md`.

---


