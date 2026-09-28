# Modell- und Anbieterregister

**Wer liefert die KI, die bei euch entscheidet — und was hat er zugesagt?** Ein Register für KI-Anbieter, Basismodelle und eingebettete Komponenten, samt der Fragen, die vor dem Vertrag gestellt gehören.

*A register for AI vendors, foundation models and embedded components, with the procurement questions that belong before the contract.*

---

## Das Problem

Die meisten KI-Systeme in einem Unternehmen wurden nicht dort gebaut. Sie stecken in eingekaufter Software, hängen an einer API oder sind ein Feature, das ein Anbieter im letzten Release ergänzt hat. Wer bei der Bestandsaufnahme nur nach „unseren KI-Projekten" fragt, findet den kleineren Teil.

Das Anbieterregister beantwortet drei Fragen, die im Prüfungsfall gestellt werden:

1. **Welche KI beziehen wir von wem?**
2. **Was hat der Anbieter vertraglich und dokumentarisch zugesagt?**
3. **Was ändert sich, wenn er etwas ändert?**

## Fünf Kategorien

| Kategorie | Beispiel | Worauf es ankommt |
|---|---|---|
| **Basismodell** | Sprach- oder Bildmodell als Grundlage | Trainingsnutzung, Modellversion, GPAI-Dokumentation |
| **API-Dienst** | Übersetzung, Klassifikation, Spracherkennung als Dienst | Verarbeitungsort, Unterauftragsverarbeiter, Verfügbarkeit |
| **Eingebettete Komponente** | KI-Funktion in gekaufter Standardsoftware | oft unbemerkt; Änderung ohne Ankündigung |
| **Datenlieferant** | Trainings- oder Anreicherungsdaten | Herkunft, Rechtegrundlage, Qualität |
| **Sonstige** | alles, was nicht passt | |

Die dritte Kategorie ist die gefährlichste, weil sie niemand beantragt hat. Ein CRM bekommt eine Zusammenfassungsfunktion, ein Bewerbungstool eine Vorsortierung — und plötzlich verarbeitet ein KI-System Bewerberdaten, ohne dass ein Projekt dazu existiert.

## Drei Rollen, die man auseinanderhalten muss

Ein und derselbe Anbieter kann gleichzeitig sein:

- **KI-Anbieter** im Sinne des AI Act — er stellt das System bereit
- **Auftragsverarbeiter** im Sinne der DSGVO — er verarbeitet Daten in eurem Auftrag
- **Empfänger** — er bekommt Daten für eigene Zwecke

Die drei lösen unterschiedliche Pflichten aus und werden im Register getrennt gekennzeichnet. Wer sie vermengt, hat im Zweifel einen AVV für eine Weitergabe, die keine Auftragsverarbeitung ist — oder umgekehrt.

## Inhalt

| Dokument | Inhalt |
|---|---|
| [Was ins Register gehört](./knowledge-base/registerfelder.md) | Felder, Rollen, Klassifizierung, Prüfzyklus |
| [Fragen vor dem Vertrag](./knowledge-base/beschaffung.md) | Was ein Anbieter liefern muss, und was tun, wenn er es nicht tut |
| [Wenn der Anbieter etwas ändert](./knowledge-base/anbieteraenderungen.md) | Versionswechsel, stille Änderungen, Nachweisführung |
| [Vorlage: Registereintrag](./templates/registereintrag.md) | Zum Ausfüllen |
| [Vorlage: Anbieterfragebogen](./templates/anbieterfragebogen.md) | Zum Versenden |

## Verwandtes Verzeichnis

Für die Frage, was einzelne Anbieter **tatsächlich** pro Tarif zusagen — Auftragsverarbeitung, Trainingsnutzung, Verarbeitungsort, Unterauftragsverarbeiter — führt SimpleAct ein öffentliches Register mit Quelle und Prüfdatum je Angabe: **[actcomp.de](https://actcomp.de)**

## In Software umsetzen

[SimpleAct](https://simpleact.de) führt Anbieter- und Modellregister verknüpft mit KI-Inventar, Verarbeitungsverzeichnis und AVV-Verwaltung: **[Vendor Register](https://simpleact.de/ki-register)**

## Stand und Lizenz

Zuletzt aktualisiert: 2026-09-28 · MIT — frei nutzbar, auch kommerziell. Keine Rechtsberatung.
