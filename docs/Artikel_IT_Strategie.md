# IT-Strategie für einen Mittelständler: Von einer gewachsenen Systemlandschaft zu S/4HANA

*Von Bayrem Trabelsi, gemeinsam mit Sarah Hauschildt. Fallstudie im Modul Informationsmanagement (M.Sc. Wirtschaftsinformatik, Hochschule Worms). Das Unternehmen Ratzfatz ist ein fiktiver Lehrfall.*

---

## Die Ausgangslage

Ein Hersteller von Waschmaschinen, Großwaschanlagen und Reinigungsmitteln hat über Jahre eine heterogene IT gesammelt: SAP ERP ECC 6.0 für Finanzen und Controlling, ein Cobol-ERP, eine Eigenentwicklung für das Reinigungsmittelwerk, Lotus Notes, Access-Datenbanken, Excel und eigene CAD-Systeme. Prozesse sind nicht integriert und nur teilweise automatisiert. Mitarbeitende verlieren Zeit durch manuelle Abläufe.

## Schritt 1: Von der Unternehmensstrategie zur IT

Die IT-Strategie wird aus der Unternehmensstrategie abgeleitet, nicht aus Technologietrends. Wir haben dafür die Produkte in einer **BCG-Matrix** [1] eingeordnet (Waschmaschinen, Großwaschanlagen, Reinigungsmittel), die Wettbewerbssituation nach **Porter** [2] betrachtet (Differenzierung bei Waschmaschinen, Kostenführerschaft bei Reinigungsmitteln, Nischenstrategie bei Großwaschanlagen) und daraus Handlungsstränge für die IT abgeleitet: einheitliche Systeme, Automatisierung, bessere Datenqualität und Schulung.

## Schritt 2: Ist-Analyse der IT

| Bereich | Befund |
|---|---|
| Projektmanagement | IT und Fachbereiche arbeiten schlecht zusammen, Commitment nur teilweise |
| Architekturmanagement | viele veraltete Systeme, keine Ablösepläne, viel Schatten-IT |
| Stammdaten | keine einheitliche Datenstruktur, Daten nicht ausreichend geprüft |
| Softwareentwicklung | kein einheitlicher Entwicklungsprozess, wenig Dokumentation |
| IT-Service und Compliance | Support nur per E-Mail oder Telefon, kein Lizenzmanagement, keine Archivierung |

## Schritt 3: Soll-Architektur

- **Kern:** SAP S/4HANA mit HANA-Cloud und rollenbasierter Oberfläche (Fiori), siehe [3]
- **Zusammenarbeit:** Microsoft 365 (Teams, SharePoint, Outlook)
- **Steuerung:** Jira für Tickets und Projektplanung
- **Konstruktion:** ein einheitliches CAD-System (Siemens NX)
- **Analyse:** Power BI und SAP Analytics
- **Zukunft:** KI zur Waschmaschinen-Zuteilung und IoT-Anbindung

## Schritt 4: Applikationsportfolio und Roadmap

Jede Anwendung wurde nach Wartungskosten, Anwenderakzeptanz, Reifegrad und Technologie bewertet. Daraus folgen vier Optionen: **behalten** (zum Beispiel Excel für unkritische Aufgaben), **aktualisieren**, **ersetzen** (Cobol-ERP, Lotus Notes, Alt-ERP) oder **abschaffen**.

Die Roadmap läuft über vier Jahre: Pilot von S/4HANA mit Finanzen und Controlling in einem kleinen Bereich, danach Rollout von Vertrieb, SCM, HR und Produktion, parallel Microsoft 365, Jira und CAD, später KI und IoT, zuletzt die Abschaltung der Altsysteme.

## Was die Arbeit nicht leistet

- Es gibt **keine Kostenschätzung** und keine Aufwandsplanung.
- Eine **Risikoanalyse** fehlt (Datenmigration, Akzeptanz, Parallelbetrieb).
- Die Roadmap ist nicht mit Ressourcen hinterlegt.

## Was ich mitnehme

1. **IT-Strategie beginnt bei der Unternehmensstrategie.** Erst wenn klar ist, wo das Unternehmen hin will, lässt sich über Systeme entscheiden.
2. **Ein Applikationsportfolio macht Ablöseentscheidungen nachvollziehbar** und hilft gegen Bauchentscheidungen.
3. **Bei ERP-Migrationen entscheiden Daten und Menschen.** Datenqualität, Schulung und ein Pilot vor dem Rollout sind wichtiger als das Produkt.

## Quellen

1. Henderson, B. D. (1970): The Product Portfolio. BCG Perspectives. https://www.bcg.com/publications/1970/strategy-the-product-portfolio
2. Porter, M. E. (1979): How Competitive Forces Shape Strategy. Harvard Business Review 57(2), S. 137–145.
3. SAP: SAP S/4HANA (Produktinformation). https://www.sap.com/products/erp/s4hana.html

*Hinweis: Preise, Herstellerangaben und Aussagen zu Produkten geben den Stand der jeweiligen Studienarbeit wieder. Alle Links wurden zuletzt im November 2026 gesucht oder abgerufen; Quellen mit dem Vermerk "wie in der Studienarbeit zitiert" sind dort im Literaturverzeichnis nachzuschlagen.*

---

*Ich suche zum 01.03.2027 den Einstieg als Junior IT Consultant oder IT Business Analyst. [LinkedIn](https://linkedin.com/in/bayremtrabelsi)*