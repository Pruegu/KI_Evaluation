# Framework zur Evaluation und Priorisierung von KI-Projekten in der Schweizer Verwaltung

## 1. Theoretische Grundlage aus der Recherche

### Zielbild
Ein KI-Portfolio in der Verwaltung sollte nicht nur nach technischer Machbarkeit sortiert werden. State-of-the-art-Ansätze kombinieren **öffentlichen Nutzen**, **Wirtschaftlichkeit**, **Umsetzbarkeit**, **Risiko/Vertrauenswürdigkeit**, **Rechtskonformität**, **Datenreife**, **Betriebsfähigkeit** und **strategische Passung**. Für die Schweiz ist zusätzlich wichtig, dass das Verfahren föderal anschlussfähig ist, also für Bund, Kantone und Gemeinden mit unterschiedlichem Reifegrad funktioniert.

### Quellenlage und gemeinsame Muster
Die ausgewerteten Quellen zeigen starke Übereinstimmungen:

* Die Schweizer Bundesverwaltung definiert KI als Teil der digitalen Transformation und verlangt verantwortungsvollen Einsatz, Effizienzsteigerung sowie Einhaltung von Datenschutz und Informationssicherheit. Die KI-Teilstrategie des Bundes nennt drei Handlungsfelder: **Vertrauen verdienen**, **Effizienz steigern** und **Kompetenzen aufbauen**. Quellen: Bundeskanzlei, KI-Seite und Strategie zum Einsatz von KI-Systemen in der Bundesverwaltung; EFK-Prüfungen zu FINMA, Bundesgericht und internationalem Parallelaudit.
* Die Eidgenössische Finanzkontrolle betont bei KI-Prüfungen besonders **Wirtschaftlichkeit**, **Wirkungskontrolle**, **Vertrauenswürdigkeitsevaluation**, **Governance**, **Kompetenzaufbau**, Synergien und Skalierung über Verwaltungseinheiten hinweg. Quellen: EFK-Prüfung FINMA, EFK-Prüfung Chatbots, EFK internationaler Parallelaudit.
* Die EU operationalisiert vertrauenswürdige KI über ALTAI mit Anforderungen an menschliche Aufsicht, technische Robustheit, Datenschutz, Transparenz, Fairness, gesellschaftliches Wohlergehen und Rechenschaftspflicht. Quelle: EU-Kommission, ALTAI.
* Kanada nutzt eine verpflichtende Algorithmic Impact Assessment für automatisierte Entscheidungssysteme mit Fragen zu Systemdesign, Algorithmus, Entscheidungstyp, Auswirkungen und Daten; abhängig vom Impact-Level folgen strengere Pflichten. Quellen: Treasury Board of Canada Secretariat, Directive on Automated Decision-Making und AIA.
* UK stellt Transparenz und öffentliche Nachvollziehbarkeit in den Vordergrund. Der Algorithmic Transparency Recording Standard verlangt strukturierte Angaben dazu, warum und wie algorithmische Tools eingesetzt werden; das AI Playbook ergänzt sichere, effektive und verantwortliche Nutzung. Quellen: GOV.UK ATRS und AI Playbook.
* Australien nutzt ein AI Impact Assessment Tool und ein AI Assurance Framework, um Auswirkungen und Risiken gegen Ethikprinzipien zu identifizieren, zu bewerten und zu managen; die nationale Assurance-Logik setzt auf Lebenszyklus-Governance. Quellen: digital.gov.au AI Impact Assessment Tool, AI Assurance Framework, AI Policy.
* Die Niederlande arbeiten mit FRAIA/IAMA, einem Grundrechte- und Algorithmus-Impact-Assessment. Der Fokus liegt besonders auf Grundrechten, öffentlichen Werten, Diskriminierungsrisiken, Transparenz und Rechtfertigung staatlichen Handelns. Quellen: Government.nl FRAIA und niederländische Digital-Government-Informationen zu Algorithmen.
* Singapur betont AI Governance Testing, Benchmarking und Red-Teaming, insbesondere über AI Verify und Project Moonshot, sowie klare nationale Ziele für vertrauenswürdige, wachstumsorientierte und inklusive Digitalisierung. Quellen: Smart Nation Singapore.
* Nordische Quellen betonen menschenzentrierte Dienste, ethisch nachhaltige KI, Privacy, Cybersicherheit, Sandbox-Ansätze und Kompetenzaufbau; Finnland mit AuroraAI und Norwegen mit nationaler KI-Strategie. Quellen: EU AI Watch Finland, AuroraAI, Norwegian AI Strategy.
* Österreich/BRZ sieht KI als Technologiethema für die digitale Verwaltung, legt aber ebenfalls Wert auf Data Governance, digitale Souveränität, Sicherheit, Expert-in-the-Loop und praktische Anwendungsfälle wie Anonymisierung, Suche, Betrugsbekämpfung und Softwareentwicklung. Quelle: BRZ Technologieradar.

### Konsolidierte Kriteriensystematik
Aus den Quellen ergeben sich acht Hauptgruppen. Sie decken die wiederkehrenden Gemeinsamkeiten ab und lassen Raum für Einzelkriterien, die nur in einzelnen Ländern besonders stark ausgeprägt sind.

| Gruppe | Zweck | Häufige Einzelkriterien |
|---|---|---|
| A. Strategische und öffentliche Relevanz | Prüft, ob der Use Case politisch, fachlich und gesellschaftlich relevant ist. | Verwaltungsauftrag, Strategiepassung, Bürger-/Unternehmensnutzen, Beitrag zu Servicequalität, Skalierbarkeit über föderale Ebenen, Sichtbarkeit, Innovationssignal, Beitrag zu Nachhaltigkeit und Inklusion. |
| B. Nutzen und Wirkung | Bewertet erwartbare Wirkung und Messbarkeit. | Zeitersparnis, Kostenreduktion, Qualitätsgewinn, Fehlerreduktion, schnellere Verfahren, bessere Zugänglichkeit, Risikoreduktion, Mitarbeitendenentlastung, Wirkungskontrolle, KPI-Baseline. |
| C. Kosten und Ressourcen | Macht Projekte kosten-nutzen-vergleichbar. | Einmalige Investitionen, Betriebskosten, Datenaufbereitung, Integration, Beschaffung, Lizenzen, Cloud-/Compute-Kosten, Fachexpertenzeit, Schulung, Change Management, Audit und Monitoring. |
| D. Machbarkeit und Lieferfähigkeit | Prüft, ob das Vorhaben realistisch umgesetzt werden kann. | Prozessreife, Datenverfügbarkeit, Datenqualität, technische Integration, Schnittstellen, Beschaffbarkeit, Lieferantenabhängigkeit, Projektkomplexität, Pilotierbarkeit, vorhandene Kompetenzen, Betriebsmodell. |
| E. Recht, Ethik und Grundrechte | Entscheidet über Zulässigkeit und Schutzbedarf. | Rechtsgrundlage, Datenschutz, Informationssicherheit, Amtsgeheimnis, Diskriminierungsrisiko, Grundrechte, Erklärbarkeit, Transparenz, Rechenschaft, Einsprache-/Rekursfähigkeit, menschliche Aufsicht. |
| F. Risiko und Vertrauenswürdigkeit | Bewertet Schadenspotenzial und Kontrollbedarf. | Impact-Level, Sicherheitsrisiken, Fehlentscheidungen, Halluzinationen, Robustheit, Bias, Missbrauch, Abhängigkeit von proprietären Modellen, Modell-Drift, reputative Risiken, Notfall-/Fallback-Prozesse. |
| G. Governance und Betrieb | Sichert nachhaltige Verantwortung über den Lebenszyklus. | Product Owner, Fachverantwortung, Datenverantwortung, Modellverantwortung, Freigaben, Dokumentation, Auditierbarkeit, Monitoring, Incident-Prozess, Register-/Transparenzpflichten, Wiederverwendbarkeit. |
| H. Kompetenzen und Organisation | Prüft, ob die Verwaltung die Lösung sinnvoll nutzen kann. | AI Literacy, Fachkompetenz, Schulung, Akzeptanz, Personalvertretung, Change Readiness, Expert-in-the-Loop, Kommunikationsfähigkeit gegenüber Bevölkerung und Politik. |

### Einzelkriterien, die besonders hervorstechen
Neben den stark geteilten Kriterien gibt es länderspezifische Akzente, die für die Schweiz nützlich sind:

* **Wirkungskontrolle als Pflichtdisziplin**: Die EFK kritisiert fehlende Messung von Nutzung, Effizienz und Vertrauenswürdigkeit. Deshalb sollte kein KI-Projekt ohne Baseline, Ziel-KPI und Post-Implementation-Review aufgenommen werden.
* **Grundrechte-Impact als eigene Prüfung**: Die niederländische FRAIA zeigt, dass Datenschutz allein nicht reicht; Gleichbehandlung, Zugang zu Leistungen, Verfahrensrechte und öffentliche Werte müssen explizit geprüft werden.
* **Transparenzregister**: Der UK ATRS ist für die Schweiz anschlussfähig, weil föderale Behörden verständliche öffentliche Angaben zu Zweck, Einsatz, Daten, menschlicher Kontrolle und Kontaktstelle publizieren könnten.
* **Impact-Level statt One-size-fits-all**: Kanada und Australien zeigen, dass risikobasierte Pflichten praktikabler sind als ein einheitliches schweres Verfahren für alle KI-Ideen.
* **Testing, Red-Teaming und kontinuierliche Assurance**: Singapur und Australien betonen, dass Evaluation nicht beim Projektentscheid endet, sondern Modelltests, Monitoring und Lebenszyklus-Assurance verlangt.
* **Digitale Souveränität und Wiederverwendbarkeit**: Österreich/BRZ und Schweizer EFK-Quellen machen deutlich, dass Synergien, Standardplattformen und Abhängigkeiten in die Priorisierung gehören.

## 2. Anwendungsorientiertes Framework für die Schweizer Verwaltung

### Designprinzipien
Das Framework trennt drei Rollen und drei Detailstufen:

1. **Intake durch Fachbereiche**: Niederschwelliger Fragebogen in Alltagssprache. Ziel ist nicht perfekte Bewertung, sondern strukturierte Erfassung.
2. **Bewertung durch Profis**: Portfolio-/Digitalisierungs-/Rechts-/Datenschutz-/IT-Sicherheits-/Finanzexpertinnen bewerten mit Skalen, Evidenz und Risikoklassen.
3. **Entscheidung durch Geschäftsleitung**: Verdichtete Portfolio-Sicht mit Ampeln, Nutzen-Kosten-Position, Risiken, Entscheidoptionen und klarer Empfehlung.

### Prozessmodell

| Phase | Ergebnis | Verantwortlich |
|---|---|---|
| 0. Vorfilter | KI-Relevanz, Verwaltungsrelevanz, No-Go-Kriterien | Intake-Stelle / Portfolio Office |
| 1. Intake Light | Use-Case-Steckbrief in einfacher Sprache | Fachbereich |
| 2. Triage | Einordnung in Projektart und Impact-Level | KI-/Digital-Team mit Recht/DSB/ISB |
| 3. Vollbewertung | Bewertungsmatrix, Kosten-Nutzen-Modell, Risikoauflagen | Fachexpertenpanel |
| 4. Portfolio-Priorisierung | Rangliste und Bubble-Chart | Portfolio Board |
| 5. GL-Entscheid | Go / Pilot / Zurückstellen / Ablehnen / Zusammenlegen | Geschäftsleitung |
| 6. Pilot-Gate | Nachweis von Wirkung, Sicherheit und Akzeptanz | Projektteam + Assurance |
| 7. Betriebsgate | Freigabe mit Monitoring, Register, Review-Termin | Linie / Betrieb / Governance |

### Phase 0: Vorfilter mit No-Go- und Fast-Track-Regeln

**No-Go oder Stop bis Klärung**:

* Kein plausibler Bezug zu gesetzlichem Auftrag oder Verwaltungsleistung.
* Keine verantwortliche Fachstelle.
* Verarbeitung sensibler oder geheimer Daten ohne erste Datenschutz-/Informationssicherheitsklärung.
* Vollautomatisierte belastende Entscheidung gegenüber Personen ohne klare Rechtsgrundlage, menschliche Aufsicht und Rechtsmittelkonzept.
* Kein realistischer Datenzugang.
* Reiner Technologieversuch ohne Lernziel, Nutzenhypothese oder Wiederverwendungspotenzial.

**Fast Track für Experimente**:

* Keine personenbezogenen oder klassifizierten Daten.
* Nur interne Assistenzfunktion ohne Entscheidwirkung gegenüber Bevölkerung oder Unternehmen.
* Begrenzter Nutzerkreis, kurzer Zeitraum, dokumentiertes Lernziel.
* Keine Integration in produktive Fachverfahren.

### Phase 1: Intake Light für nicht spezialisierte Antragstellende

Der Intake sollte maximal 20 bis 30 Minuten dauern und bewusst einfache Fragen nutzen:

| Frage | Antwortformat |
|---|---|
| Welches Problem soll gelöst werden? | Freitext, 3–5 Sätze |
| Wer hat heute den Aufwand oder das Problem? | Bürger/Unternehmen/Mitarbeitende/andere Behörden |
| Was passiert heute manuell oder langsam? | Freitext |
| Was soll die KI ungefähr tun? | Text verstehen, Dokumente suchen, Fälle priorisieren, Prognose, Chatbot, Klassifikation, Anonymisierung, Übersetzung, andere |
| Welche Entscheidung oder Handlung wird beeinflusst? | Keine / Empfehlung / Vorbereitung / Entscheidungsvorschlag / automatische Entscheidung |
| Gibt es Auswirkungen auf Rechte, Pflichten, Leistungen oder Kontrollen von Personen? | Ja/Nein/Unklar |
| Welche Daten wären nötig? | Dokumente, Falldaten, Personendaten, besondere Personendaten, öffentliche Daten, unklar |
| Gibt es bereits Beispiele oder Lösungen? | Link/Freitext |
| Wie oft tritt der Fall auf? | selten / monatlich / wöchentlich / täglich / massenhaft |
| Was wäre ein messbarer Erfolg? | Zeit, Kosten, Qualität, Zugang, Risiko, Zufriedenheit |
| Wer kann fachlich testen, ob die KI richtig liegt? | Name/Rolle |
| Bis wann wäre ein Ergebnis nützlich? | Datum/Zeitraum |

### Phase 2: Triage und Impact-Level

Empfohlene Schweizer Impact-Level:

| Level | Beschreibung | Mindestanforderungen |
|---|---|---|
| L0 Experiment | Sandbox ohne produktive Daten und ohne Aussenwirkung. | Kurzsteckbrief, Lernziel, Löschkonzept. |
| L1 Interne Assistenz | Unterstützt Mitarbeitende, keine direkten Auswirkungen auf Personen. | Datenschutz-/IS-Check, Nutzungsregeln, Human-in-the-loop. |
| L2 Operative Unterstützung | Beeinflusst Priorisierung, Qualitätssicherung oder Vorbereitung von Verwaltungshandeln. | Vollbewertung, Testplan, Monitoring, Dokumentation. |
| L3 Entscheidunterstützung mit Personenwirkung | Kann Leistungen, Pflichten, Kontrollen oder Verfahren beeinflussen. | Rechtsgrundlage, DPIA/DSFA, Grundrechte-Assessment, Bias-Test, Transparenz, Rekurs-/Erklärkonzept. |
| L4 Hochrisiko / automatisierte Entscheidung | Automatisiert oder prägt belastende Entscheide wesentlich. | GL-Freigabe, externe/ unabhängige Assurance, strenge menschliche Aufsicht, Audit, Register, laufende Evaluation. |

### Phase 3: Bewertungsmatrix für Profis

Die folgende Matrix erzeugt Vergleichbarkeit. Bewertung je Kriterium von 1 bis 5; Gewichtung kann je Organisation angepasst werden.

| Hauptkriterium | Gewicht | Leitfrage | Score 1 | Score 5 |
|---|---:|---|---|---|
| Öffentlicher Nutzen | 15% | Wie stark verbessert der Use Case Leistungen für Bevölkerung, Wirtschaft oder Verwaltung? | kaum Nutzen | hoher, breit wirksamer Nutzen |
| Strategische Passung | 8% | Passt das Vorhaben zu Strategie, gesetzlichem Auftrag und politischer Priorität? | Randthema | Kernauftrag/Strategieanker |
| Wirtschaftlicher Nutzen | 15% | Wie plausibel sind Einsparungen, Produktivität oder vermiedene Kosten? | nicht messbar | klar quantifiziert und erheblich |
| Qualitäts-/Risikonutzen | 10% | Verbessert KI Qualität, Fehlervermeidung, Sicherheit oder Compliance? | kein Effekt | deutliche Risikoreduktion |
| Datenreife | 10% | Sind Daten verfügbar, rechtmässig nutzbar, qualitativ ausreichend und dokumentiert? | ungeklärt/schlecht | verfügbar, sauber, repräsentativ |
| Technische Machbarkeit | 8% | Ist Integration, Modellwahl, Betrieb und Skalierung realistisch? | sehr unsicher | Standardlösung/geringe Komplexität |
| Organisatorische Machbarkeit | 8% | Gibt es Owner, Kompetenzen, Akzeptanz und Prozessreife? | kein Owner/geringe Reife | klare Verantwortliche und Kapazität |
| Recht/Ethik/Grundrechte | 10% | Sind rechtliche und ethische Anforderungen erfüllbar? | hohe ungeklärte Risiken | geringe Risiken/gute Kontrollen |
| Vertrauenswürdigkeit & Sicherheit | 8% | Sind Robustheit, Erklärbarkeit, Cybersecurity und Monitoring beherrschbar? | kaum kontrollierbar | gut test- und auditierbar |
| Skalierung & Wiederverwendung | 5% | Lässt sich die Lösung in anderen Ämtern/Kantonen/Gemeinden nutzen? | Einzelfall | Plattform-/Musterlösung |
| Nachhaltigkeit & Souveränität | 3% | Sind Abhängigkeiten, Energie, Beschaffung und Exit beherrscht? | Lock-in/unklar | souverän, nachhaltig, exitfähig |

**Formel**: `Gesamtscore = Summe(Score 1–5 × Gewicht)`. Zusätzlich werden **Risikoampeln** geführt; ein hoher Nutzen darf kritische rote Risiken nicht automatisch übersteuern.

### Kosten-Nutzen-Vergleich

Für Geschäftsleitungen braucht es eine einfache, aber belastbare Darstellung:

#### Kostenblöcke

* Initialkosten: Discovery, Datenanalyse, Prototyp, Beschaffung, Architektur, Entwicklung, Integration, Rechts-/DSFA-/Security-Aufwand.
* Betriebskosten: Lizenzen, Hosting/Cloud/Compute, Support, Monitoring, Modellpflege, Evaluation, Security, Registerpflege.
* Organisationskosten: Schulung, Prozessanpassung, Kommunikation, Change Management, Fachtests.
* Risikokosten: Fehlentscheidungen, manuelle Nachkontrollen, Reputationsrisiken, Lieferantenwechsel, Exit-Kosten.

#### Nutzenblöcke

* Quantifizierbar: Stundenersparnis, kürzere Durchlaufzeiten, weniger Rückfragen, weniger Fehler, vermiedene externe Kosten, höhere Fallkapazität.
* Qualitativ: bessere Zugänglichkeit, konsistentere Qualität, Mitarbeitendenentlastung, politische Sichtbarkeit, Innovationsfähigkeit, bessere Entscheidgrundlagen.
* Risikoreduktion: bessere Anomalieerkennung, frühere Erkennung von Missbrauch, bessere Dokumentation, Compliance-Verbesserung.

#### Priorisierungslogik

| Portfolio-Kategorie | Nutzen | Machbarkeit | Risiko | Empfehlung |
|---|---|---|---|---|
| Quick Win | hoch | hoch | tief/mittel | rasch pilotieren |
| Strategische Wette | hoch | mittel/tief | mittel/hoch | Discovery und kontrollierter Pilot |
| Pflichtprojekt | mittel/hoch | variabel | oft hoch | wegen Compliance/Strategie priorisieren, mit Auflagen |
| Lernexperiment | unklar | hoch | tief | kurzer Sandbox-Test |
| Parken | tief | tief/mittel | beliebig | zurückstellen |
| Ablehnen | tief oder unzulässig | tief | hoch | nicht weiterverfolgen |

### Geschäftsleitungs-Scorecard

Für die finale Entscheidung sollte jedes Projekt auf einer Seite dargestellt werden:

* Problem und Ziel in einem Satz.
* Betroffene Anspruchsgruppen.
* Erwarteter Nutzen: CHF/Jahr, Stunden/Jahr, Qualitäts-KPI, Service-KPI.
* Gesamtkosten über 3 bis 5 Jahre.
* Nutzen-Kosten-Verhältnis und Payback.
* Impact-Level L0 bis L4.
* Top-3-Risiken und Auflagen.
* Entscheidoption: Go, Pilot, Discovery, Zusammenlegen, Zurückstellen, Ablehnen.
* Nächster Gate-Termin und Erfolgskriterien.

### Empfohlene Mindestartefakte

| Artefakt | Ab Level | Zweck |
|---|---:|---|
| Use-Case-Steckbrief | L0 | einheitlicher Intake |
| Datensteckbrief | L1 | Datenquelle, Qualität, Rechtmässigkeit |
| Kosten-Nutzen-Kalkulation | L1 | Vergleichbarkeit |
| Risiko- und Impact-Assessment | L2 | risikobasierte Steuerung |
| Datenschutz-Folgenabschätzung / Vorprüfung | L2/L3 | Datenschutzkonformität |
| Grundrechte-Assessment | L3 | Fairness, Gleichbehandlung, Verfahrensrechte |
| Modell-/Systemkarte | L2 | Dokumentation von Zweck, Grenzen, Tests |
| Transparenzregister-Eintrag | L2/L3 | öffentliche Nachvollziehbarkeit |
| Monitoring- und Wirkungsplan | L2 | Betriebskontrolle |
| Exit- und Fallback-Konzept | L3 | Resilienz und Souveränität |

## 3. Referenzen

* Bundeskanzlei BK: Künstliche Intelligenz in der Bundesverwaltung, https://www.bk.admin.ch/de/ki
* Bundeskanzlei BK: Einsatz von KI in der Bundesverwaltung und KI-Teilstrategie, https://www.bk.admin.ch/de/einsatz-von-ki-in-der-bundesverwaltung
* Bundeskanzlei BK: SB021 Strategie Einsatz von KI-Systemen in der Bundesverwaltung, https://www.bk.admin.ch/de/sb021-strategie-einsatz-von-ki-systemen-in-der-bundesverwaltung
* Bundesrat/BAKOM/SBFI: Leitlinien Künstliche Intelligenz für den Bund, https://www.bakom.admin.ch/de/ki-leitlinien
* Eidgenössische Finanzkontrolle: Einsatz Künstlicher Intelligenz in der Aufsichtstätigkeit, https://www.efk.admin.ch/prufung/einsatz-kunstlicher-intelligenz-in-der-aufsichtstatigkeit/
* Eidgenössische Finanzkontrolle: Internationaler Parallelaudit zur Künstlichen Intelligenz, https://www.efk.admin.ch/prufung/internationaler-parallelaudit-zur-kunstlichen-intelligenz/
* Eidgenössische Finanzkontrolle: Prüfung der Synergien beim Einsatz von KI am Beispiel Chatbot-Lösungen, https://www.efk.admin.ch/
* Europäische Kommission: Assessment List for Trustworthy Artificial Intelligence, https://digital-strategy.ec.europa.eu/en/library/assessment-list-trustworthy-artificial-intelligence-altai-self-assessment
* Treasury Board of Canada Secretariat: Algorithmic Impact Assessment, https://www.canada.ca/en/government/system/digital-government/digital-government-innovations/responsible-use-ai/algorithmic-impact-assessment.html
* Treasury Board of Canada Secretariat: Directive on Automated Decision-Making, https://www.tbs-sct.canada.ca/pol/doc-eng.aspx?id=32592
* GOV.UK: Algorithmic Transparency Recording Standard, https://www.gov.uk/government/collections/algorithmic-transparency-recording-standard-hub
* GOV.UK: AI Playbook for the UK Government, https://www.gov.uk/government/publications/ai-playbook-for-the-uk-government/artificial-intelligence-playbook-for-the-uk-government-html
* Australian Government: AI Impact Assessment Tool, https://www.digital.gov.au/ai/impact-assessment-tool
* Australian Government: Policy for the responsible use of AI in government, https://www.digital.gov.au/ai/ai-in-government-policy
* NSW Government / Australian Government Architecture: NSW AI Assessment Framework, https://architecture.digital.gov.au/design/nsw-artificial-intelligence-assessment-framework
* Government of the Netherlands: Fundamental Rights and Algorithms Impact Assessment, https://www.government.nl/documents/reports/2021/07/31/impact-assessment-fundamental-rights-and-algorithms
* Netherlands Digital Government: Algorithms dossier, https://www.nldigitalgovernment.nl/dossiers/algorithms/
* Smart Nation Singapore: National AI Strategy and AI Verify/Moonshot references, https://www.smartnation.gov.sg/initiatives/national-ai-strategy/
* Smart Nation Singapore: Frameworks and blueprints, https://www.smartnation.gov.sg/publications/frameworks-and-blueprints/
* BRZ Österreich: Technologieradar 2024/2025, https://www.brz.gv.at/
* European Commission AI Watch: Finland public sector dimension of AI strategy, https://ai-watch.ec.europa.eu/finland-public-sector-dimension-ai-strategy_en
* Finnish Ministry of Finance: AuroraAI development and implementation plan, https://vm.fi/documents/10623/1464506/AuroraAI%2Bdevelopment%2Band%2Bimplementation%2Bplan%2B2019%E2%80%932023.pdf
* Norwegian Government: National Strategy for Artificial Intelligence, https://www.regjeringen.no/contentassets/1febbbb2c4fd4b7d92c67ddd353b6ae8/en-gb/pdfs/ki-strategi_en.pdf
