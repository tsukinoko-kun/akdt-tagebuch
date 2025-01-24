# 24.01.2025

*Die letzten Einträge waren nicht gelungen aber ich kann jetzt zum Ende nicht mehr aus meiner Perspektive von vor mehreren Monaten berichten. In diesem Eintrag reflektiere ich jedoch rückblickend über den gesamten Zeitraum des Kurses.*

*Mir ist bewusst, dass sich mein Lerntagebuch wie eine Kritik am Kurs liest. Ich kritisiere den Kurs auch, weil ich nicht herausfinden konnte, wie ich mit ihm sinnvoll lernen soll. Es geht hier also um mein Lernen. Aber es geht auch darum, wieso ich nicht so lernen konnte wie ich gerne gewollt hätte und was meine Gedanken dazu sind.*

## Meine Lernziele und Herangehensweise

Als Entwickler mit Schwerpunkt auf praktischer Implementierung wollte ich im Kurs:

1. **Problemlösungsmuster** für Quantenalgorithmen verstehen (nicht nur physikalische Modelle).
2. Lernen, wie man **reale Probleme** in quantenmechanische Abstraktionen übersetzt.
3. Erfahrung mit **Workflows** sammeln (vom Konzept zum Code in Libraries wie Qiskit).

Mein bisheriges Wissen: Grundlagen der Quantenlogik (Qubits, Gatter).

---

## Herausforderungen beim Lernen

### Fehlende iterative Anwendungsbeispiele

Programmierung lernte ich bisher am besten durch ausprobieren und Probleme lösen. Im Kurs dominierte jedoch:
- Theoretische Quantenphysik (z.B. mathematische Formalismen zur Verschränkung)
- Isolierte Konzepte ohne Bezug zu algorithmischen Patterns

**Beispiel**

Um das BB84-Protokoll (mein Kursprojekt) zu implementieren, benötigte ich:
- Verständnis für Quantenkey Distribution **auf Code-Ebene**
- Wissen zur Fehlerbehandlung

Stattdessen verbrachte ich Zeit mit abstrakter Quantenmechanik, die für die Implementierung irrelevant war.

### Diskrepanz zwischen Vorwissen und Kursfokus

Mir fehlte:
- Methodik, um **eigene Problemstellungen** in Quantenschaltkreise zu übersetzen
- Verständnis dafür, **wann** Quantenalgorithmen sinnvoll sind (vs. klassische Ansätze)

Der Kurs beantwortete diese Fragen nicht, da er sich auf vordefinierte Quantenphysik und Algorithmen beschränkte.

### Lernstil-Konflikt

Ich lerne effektiv durch:

1\. Praxisbeispiel → 2. Reverse Engineering → 3. Theoretische Vertiefung

Der Kurs folgte jedoch:

1\. Theorie → 2. Theorie → 3. Implementierung eines "Hello World"-Algorithmus

Dadurch blieben zentrale Fragen für mich offen:

- Wie strukturiere ich ein Quantenprogramm für ein **neues Problem**?
- Wie debugge ich Quantenzustände außerhalb von Toy Examples?

---

## Erkenntnisse und Anpassungsstrategien

### Was ich gelernt habe

- **BB84-Protokoll**: Umsetzung von Quantenkey Distribution in Code (Qiskit)
- **Limitationen vordefinierter Algorithmen**: Sie bieten wenig Einblick in kreative Quantenprogrammierung
- **Selbststudienbedarf**: Frameworks wie Cirq/IBM Quantum bieten bessere Praxisressourcen als der Kurs

### Wie ich mein Lernen anpasse

Um meine Ziele dennoch zu erreichen, werde ich:

1. **Eigene Mini-Projekte** entwickeln (z.B. Quanten-Version klassischer Algorithmen)
2. **Programme Analysieren**: Nach Open-Source-Programmen suchen, die Quanten Algorithmen verwenden.

---

## Fragen an mich selbst

- Wie kann ich **Transferlernen** aus klassischer Softwareentwicklung nutzen? (z.B. Parallelisierung, Komplexitätsanalyse)
- Welche Tools fehlen mir, um Quantenprogramme **iterativ** zu entwickeln? (z.B. Äquivalenz zu Debuggern)
- Wie identifiziere ich **"Quanten-taugliche" Problemstellungen** ohne Kursguidance?

Wir hatten schon im Kurs über Komplexitätsanalyse gesprochen, und dass die Quantenprogramme theoretisch sehr ineffizient sind. Jedoch scheint sich der große Overhead zu lohnen und insgesamt zu einer besseren Laufzeit zu führen.

Mein Interesse an anderen Technologien, mit denen ich mich wohler gefühlt hätte als mit Python + Qiskit stieß auf Ablehnung.

Ich suche nach anderen Ressourcen um Quantencomputing zu lernen.
Leider gibt es nicht viel.
Das meiste ist entweder viel zu hoch für mich oder auf Kindergarten-Niveau.
