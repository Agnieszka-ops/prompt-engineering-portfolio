# 📄 Projekt 2: Automatisierter LLM-Workflow für Berichtsanalysen

Dieses Projekt zeigt, wie strukturierte PDF-Berichte automatisiert in verwertbare Entscheidungsgrundlagen überführt werden können – ganz ohne Training, rein durch strategisches Prompting.

**Anwendungsfall:**  
Ein Unternehmen oder eine Verwaltungseinheit erhält regelmäßig umfangreiche Reports (z. B. Marktanalysen, Projektberichte).  
Ziel ist es, daraus mithilfe eines LLMs in wenigen Schritten automatisch:

1. eine strukturierte Zusammenfassung zu generieren,
2. Handlungsoptionen zu entwickeln,
3. Visualisierungsvorschläge zu erhalten.

---

## 📌 Workflow in 3 Schritten

1. **PDF-Input oder Reporttext bereitstellen**
2. **Zusammenfassung erstellen (Executive Summary)**
3. **Strategische Optionen + Visualisierungsvorschläge generieren**

Die Umsetzung erfolgt in einem interaktiven [Jupyter Notebook](./notebook/report-workflow.ipynb), das alle Prompts und Prozessschritte dokumentiert.

Beispieloutputs findest du im Ordner [`generated-output`](./generated-output)

---
## Weitere Beispiele : Berichtsanalyse & Wissensauswertung

Du findest hier strukturierte Prompts zur Analyse, Zusammenfassung und Bewertung von internen Berichten.  
Die Prompts sind so gestaltet, dass sie Large Language Models (LLMs) wie GPT-4 oder Claude gezielt dazu anleiten, konkrete verwertbare Ergebnisse zu erzeugen.

---

## Übersicht der Prompts

| Datei | Anwendungsfall | Beschreibung |
|-------|----------------|--------------|
| [`/prompts/wissensreport.md`](./wissensreport.md) | Intranet-/Wissensmanagementbericht auswerten | Erkenntnisse aus niedrig genutzten Portalen identifizieren, Verbesserungsvorschläge ableiten |
| [`/prompts/projektstatus.md`](./projektstatus.md) | Projektstatus analysieren & Risiken priorisieren | Zusammenfassung + Risikoeinschätzung aus Statusberichten |
|
## 📁 Beispieleingaben & -ausgaben

Zu jedem Prompt findest du passende Beispieltexte im Ordner [`../beispiele/`](../beispiele):

- `eingabe-wissensreport.txt` & `ausgabe-wissensreport.txt`
- `eingabe-projektstatus.txt` & `ausgabe-projektstatus.txt`

Die Beispiele zeigen jeweils einen realitätsnahen Berichtstext und den erwarteten Output des LLMs.

---

## Hinweise

- Alle Prompts wurden mit Fokus auf Klarheit, Strukturierbarkeit und Modularität entwickelt
- Die Texte können direkt in einem Prompt-Tool (Playground, ChatGPT, Claude etc.) getestet werden
- Erweiterungen oder branchenspezifische Varianten sind vorgesehen

---

Für Rückfragen oder Feedback gerne Kontakt aufnehmen!
