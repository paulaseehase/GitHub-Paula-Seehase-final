# Finaler Master-Prompt (Zyklus 2, Regeln 1–8)

Wird in NotebookLM zusammen mit den hochgeladenen Quellen (Datensatz_v1 mit fünf Beispielfragebögen, Do Khac et al. 2025, Wolfe et al. 2025 und weitere Publikationen) verwendet.

```
Rolle: Du bist Expertin für die Konstruktion wissenschaftlicher Fragebögen in der Organisationsforschung.

Aufgabe: Erstelle einen Fragebogen zur Messung der KI-Readiness von Mitarbeitenden in Unternehmen auf Basis des folgenden theoretischen Modells.

Theoretisches Modell (integriertes Appraisal-Modell, erweitert um Trust und Anxiety):
| Kategorie | Konstrukt | Quelle |
| Adaptive Appraisals | Attitude (KI-Nutzung) | Wichmann et al. |
| Adaptive Appraisals | Perceived Response Efficacy | Wichmann et al. |
| Adaptive Appraisals | Perceived Behavioral Control | Wichmann et al. |
| Adaptive Appraisals | Trust (inkl. Ability, Integrity, Benevolence) | Do Khac et al. |
| Non-adaptive Appraisals | Anxiety (KI-spezifisch) | Wolfe et al. |
| Non-adaptive Appraisals | Perceived Vulnerability (Jobrisiko) | Wichmann et al., adaptiert |
| Moderierend | Perceived Norms | Wichmann et al. |
| Ergebnis | Intention to Use / KI-Readiness | – |

Stilvorbild: Orientiere dich an Formulierungsstil, Itemlänge und Antwortskalen der fünf in den Quellen hinterlegten Beispielfragebögen (Datensatz_v1), nicht an deren Inhalt.

Regeln:
1. Erstelle für jedes der 7 Konstrukte genau 3 Items (insgesamt 21 Items).
2. Jedes Item ist eine einzelne, in sich geschlossene Aussage (kein "und"-verknüpftes Doppel-Item / keine double-barreled questions).
3. Keine Suggestiv- oder Lenkungsformulierungen (z. B. "Finden Sie nicht auch...").
4. Verwende eine 5-stufige Likert-Skala ("stimme gar nicht zu" bis "stimme voll zu") einheitlich für alle Items.
5. Items müssen für Mitarbeitende ohne KI-Vorwissen verständlich formuliert sein (keine Fachbegriffe wie "Appraisal" oder "Trust" im Item selbst).
6. Formuliere alle Items konsistent in der Höflichkeitsform ("Sie").
7. Verknüpfe in einem Item niemals zwei trennbare Sachverhalte – weder mit "und" noch mit "oder" (z. B. nicht "verändert oder ersetzt", sondern genau einen Zustand abfragen).
8. Formuliere alle Items konsequent aus der persönlichen Perspektive der befragten Person ("Sie persönlich..."), nicht aus Unternehmens- oder Teamperspektive.

Output-Format: Tabelle mit den Spalten Konstrukt | Item-Nr. | Itemformulierung | Quelle/theoretische Begründung (kurz, mit Bezug auf das jeweilige Ausgangskonstrukt).
```
