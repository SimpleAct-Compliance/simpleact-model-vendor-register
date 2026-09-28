# Was ins Register gehört

## Der Grundsatz

Ein Anbieterregister ist kein Einkaufsverzeichnis. Es hält die Angaben fest, die ihr für eure **eigene** Dokumentation braucht und die nur der Anbieter liefern kann.

Die Prüffrage für jedes Feld lautet deshalb: *Steht diese Angabe später in einer Dokumentation, die wir vorlegen müssen?* Wenn nein, gehört sie nicht ins Register.

## Felder

### Identität

| Feld | Warum |
|---|---|
| Anbieter | |
| Produkt | Anbieter haben mehrere Produkte mit unterschiedlichen Zusagen |
| **Tarif** | Zusagen unterscheiden sich pro Tarif — der wichtigste und meistvergessene Eintrag |
| Kategorie | Basismodell / API-Dienst / eingebettete Komponente / Datenlieferant |
| Modell und Version | ohne sie ist nach einem Vorfall nicht rekonstruierbar, womit gearbeitet wurde |

### Rollen

| Feld | Bedeutung |
|---|---|
| KI-Anbieter | stellt ein KI-System bereit, AI Act |
| Auftragsverarbeiter | verarbeitet Daten in eurem Auftrag, Art. 28 DSGVO |
| Empfänger | erhält Daten für eigene Zwecke |

Mehrfachnennung möglich. Jede Rolle löst andere Pflichten aus.

### Einstufung

| Feld | Werte |
|---|---|
| AI-Act-Klasse | minimal / begrenzt / hoch / verboten / nicht bewertet |
| Risikostufe | niedrig / mittel / hoch / kritisch / unbekannt |
| Compliance-Status | erfüllt / offen / nicht erfüllt / unbekannt |

**„Nicht bewertet" und „unbekannt" sind gültige Einträge.** Ein Register, in dem alles bewertet aussieht, obwohl niemand hingesehen hat, ist schlechter als eines, das seine Lücken zeigt. Die Lücke ist der Arbeitsvorrat.

### Vertragliches

| Feld | Warum |
|---|---|
| AVV vorhanden, unterzeichnet am, Fundstelle | Nachweis nach Art. 28 |
| Weitere vertragliche Zusicherungen | etwa Trainingsausschluss, Verarbeitungsort |
| Datenkategorien | was dieser Anbieter tatsächlich sieht |
| Verarbeitungsort | |
| Unterauftragsverarbeiter | |

### Betrieb

| Feld | Warum |
|---|---|
| Verknüpfte KI-Systeme | welche eurer Systeme hängen daran |
| Letzte Bewertung | |
| Nächste Prüfung | |
| Verantwortlich | eine Person, keine Abteilung |

## Prüfzyklus

Ein jährlicher Zyklus ist üblich und reicht für stabile Anbieter. Zusätzlich braucht es **ereignisgesteuerte** Prüfungen:

- Der Anbieter ändert Bedingungen, Tarifstruktur oder Unterauftragsverarbeiter
- Ein Modell- oder Versionswechsel wird bekannt
- Ein Vorfall betrifft diesen Anbieter
- Die eigene Nutzung ändert sich wesentlich — neue Datenkategorien, neue Zwecke
- Die Rechtslage ändert sich

Der zweite Punkt ist der, der ohne technische Unterstützung nicht auffällt. Wer die Modellversion nicht mitprotokolliert, erfährt vom Wechsel erst, wenn sich das Verhalten ändert.

## Verbindung zu den anderen Registern

| Register | Verbindung |
|---|---|
| KI-Inventar | welches System nutzt welchen Anbieter |
| Verarbeitungsverzeichnis | welche Verarbeitung stützt sich auf welchen Auftragsverarbeiter |
| Löschkonzept | welche Löschpflichten reicht ihr an den Anbieter durch |
| Vorfallverfahren | wen informiert ihr, wer informiert euch |

Ohne diese Verknüpfungen ist das Register eine Liste. Mit ihnen beantwortet es die Frage, die im Prüfungsfall kommt: *Welche eurer Verarbeitungen sind betroffen, wenn dieser Anbieter ausfällt oder gegen eine Zusage verstößt?*

---

Weiter: [Fragen vor dem Vertrag](./beschaffung.md) · [Anbieteränderungen](./anbieteraenderungen.md) · [Vorlage](../templates/registereintrag.md)

Keine Rechtsberatung.
