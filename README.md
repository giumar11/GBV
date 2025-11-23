# GBV
# Workflow di presa in carico nei casi di violenza di genere (Mermaid)

Questo repository contiene un diagramma in **Mermaid** che rappresenta un workflow il più possibile completo e multi-attore per la presa in carico di casi di **violenza di genere**, dalla prima emersione del disagio fino alla presa in carico continuativa, includendo:

- survivor (persona che subisce violenza),
- servizi sanitari (PS e altri servizi),
- centri antiviolenza e case rifugio,
- servizi sociali e tutela minori,
- polizia e giustizia,
- coordinamento multi-agenzia,
- misure e programmi rivolti al perpetrator (persona che agisce violenza).

L’obiettivo è offrire una **rappresentazione leggibile, verificabile e versionabile** di un processo complesso, basata su linee guida e standard internazionali e nazionali, utile per:

- formazione e sensibilizzazione,
- ricerca e analisi di percorsi sociosanitari,
- progettazione di strumenti digitali (incluse soluzioni di AI) che non scarichino la responsabilità solo sulla survivor.

> ⚠️ **Disclaimer importante**  
> Questo schema non sostituisce in alcun modo le **linee guida ufficiali**, i **protocolli locali**, né il giudizio clinico/giuridico.  
> È uno strumento concettuale per ricerca, formazione e co-progettazione.

---

## Contenuti del repository

Suggerimento di struttura:

- `diagramma_violenza_genere_full.mmd`  
  Versione completa del workflow in Mermaid (tutte le fasi in un unico diagramma).

- `diagramma_violenza_genere_blocks/`  
  - `01_ingresso_accessi.mmd` – Ingresso nel sistema e accessi multipli (CAV, PS, consultori, servizi sociali, polizia, ecc.)  
  - `02_pronto_soccorso_sanita.mmd` – Triage, percorso VAW, valutazione clinica, consenso, minori.  
  - `03_risk_assessment_decisioni_legali.mmd` – Valutazione del rischio, dimissione/ricovero/casa rifugio, referti, denuncia.  
  - `04_centro_antiviolenza_rete.mmd` – CAV, casa rifugio I/II livello, servizi sociali.  
  - `05_perpetrator_multiagenzia.mmd` – Misure legali su perpetrator, programmi per autori, gestione multi-agenzia.

- `exports/`  
  - `diagramma_full.png` / `diagramma_full.svg` – Export grafici del diagramma completo.  
  - eventuali immagini per i singoli blocchi.

- `docs/`  
  - `legenda_attori.md` – Spiegazione dei codici usati nel diagramma (`S`, `H`, `CAV`, `SS`, `P`, `NET`, `PERP` ecc.).  
  - `note_metodologiche.md` – Descrizione estesa della metodologia e delle assunzioni.

---

## Attori e prospettiva

Il workflow è costruito da una prospettiva **femminista, survivor-centred e multi-attore**, con un’attenzione esplicita a:

- **Survivor** (persona che subisce violenza)  
  - non è chiamata a “fare triage”, ma a portare esperienza, narrazione e percezione del rischio;
- **Servizi sanitari (H)** – pronto soccorso e altri servizi  
  - valutazione clinica, triage, gestione dell’urgenza, documentazione delle lesioni, raccolta di evidenze forensi se c’è consenso;
- **Centri antiviolenza e case rifugio (CAV)**  
  - accoglienza, presa in carico, piani di sicurezza, casa rifugio I e II livello, supporto alla denuncia;
- **Servizi sociali e tutela minori (SS)**  
  - valutazione e protezione di minori/persone vulnerabili, supporto abitativo, economico, lavorativo;
- **Polizia e giustizia (P)**  
  - valutazione del rischio da parte delle forze dell’ordine, misure di protezione, gestione del processo penale;
- **Coordinamento multi-agenzia (NET)**  
  - gestione congiunta dei casi ad alto rischio (es. modelli tipo MARAC / case conference);
- **Perpetrator (PERP)**  
  - misure legali, restrizioni, ed eventuali programmi di trattamento per chi agisce violenza, sempre subordinati alla sicurezza della survivor.

---

## Struttura logica del workflow

A livello concettuale, il diagramma copre queste fasi:

1. **Emersione del disagio (S)**  
   - la persona sente che “qualcosa non va” (controllo, paura, isolamento, minacce, ecc.) e decide di parlarne con qualcuno, anche in assenza di emergenza.

2. **Accessi multipli al sistema**  
   - accesso diretto a CAV / 1522, PS, consultori, MMG/ginecologia, servizi sociali, polizia, associazioni/terzo settore, persona di fiducia, ecc.

3. **Triage, sospetto di violenza e attivazione del percorso VAW**  
   - in PS: triage, assegnazione codice di urgenza, identificativo di percorso dedicato (“Percorso per le donne che subiscono violenza”),  
   - distinzione tra violenza dichiarata, violenza sospettata e assenza di indicatori, con materiale informativo sempre disponibile.

4. **Informazione, consenso e accessibilità**  
   - informazione chiara sui passi del percorso, consenso informato per raccolta dati, esami e contatti con altri servizi,  
   - rispetto della privacy, accesso a mediazione culturale/interprete e supporti per disabilità.

5. **Minori e persone vulnerabili**  
   - valutazione specifica di figli/e e altre persone vulnerabili, con eventuale attivazione di tutela minori/servizi sociali e segnalazioni obbligatorie.

6. **Valutazione clinica, psicosociale e forense**  
   - percorsi distinti per violenza fisica, violenza sessuale recente, violenza psicologica, stalking,  
   - raccolta di evidenze forensi dove previsto e con consenso.

7. **Risk assessment e decisioni sul setting di cura**  
   - integrazione tra:
     - percezione soggettiva del rischio da parte della survivor,
     - fattori di rischio clinici e criminologici (escalation, uso di armi, strangolamento, minacce di morte),
     - strumenti di valutazione del rischio raccomandati per sanità e polizia;
   - esito: rischio basso/medio vs alto/molto alto, con scelte tra:
     - dimissione con safety plan,
     - ricovero protetto,
     - casa rifugio I livello.

8. **Decisioni legali e misure sul perpetrator**  
   - referti e segnalazioni obbligatorie (es. lesioni gravi, minori, armi),  
   - scelta della survivor se presentare o meno denuncia (quando la legge lo consente),  
   - misure legali su perpetrator (ordini di protezione, allontanamento, ammonimenti, misure cautelari, ecc.),  
   - eventuale accesso a programmi per autori di violenza, senza mai sostituire le misure di protezione per la survivor.

9. **Presa in carico continuativa, casa rifugio e autonomia**  
   - percorsi CAV in esterno o in casa rifugio I/II livello,  
   - integrazione con servizi sociali, politiche abitative e di inserimento lavorativo,  
   - follow-up e rivalutazione del rischio nel tempo, con possibilità di rientro nel percorso.

---

## Metodologia

Il workflow è stato costruito tramite:

1. **Analisi documentale**  
   - linee guida nazionali italiane per il “Percorso per le donne che subiscono violenza” nelle Aziende sanitarie e ospedaliere (DPCM 24 novembre 2017),  
   - protocolli ospedalieri e regionali (es. implementazioni del “Codice Rosa”, procedure aziendali sul percorso antiviolenza),  
   - linee guida OMS per la risposta sanitaria alla violenza di genere,  
   - linee guida EIGE per il risk assessment e risk management da parte della polizia,  
   - Pacchetto di servizi essenziali (Essential Services Package) per donne e bambine soggette a violenza, elaborato dall’ONU.

2. **Sintesi concettuale**  
   - estrazione delle fasi comuni, dei decision point chiave e degli attori coinvolti,  
   - trasformazione dei testi normativi/clinici in nodi e condizioni logiche.

3. **Formalizzazione in Mermaid**  
   - uso di nodi brevi per concentrarsi su flussi e decisioni,  
   - codifica degli attori (es. `S`, `H`, `CAV`, `SS`, `P`, `NET`, `PERP`) e colori diversi per tipo di servizio,  
   - versionamento tramite file `.mmd` per facilitare contributi, fork e adattamenti locali.

4. **Approccio femminista e survivor-centred**  
   - attenzione a non scaricare su survivor la responsabilità esclusiva nella valutazione del rischio,  
   - esplicitazione del ruolo di perpetrator e dei sistemi che lo devono gestire (polizia, giustizia, eventuali programmi),  
   - inclusione di minori e persone vulnerabili come soggetti di diritti, non solo “contesto”.

---

## Come usare questo repository

Alcuni possibili usi:

- **Formazione**  
  - base per corsi destinati a operatori/trici sanitariə, sociali, dei CAV, della polizia, del terzo settore;
- **Ricerca e audit**  
  - confronto tra il workflow “ideale” e i percorsi reali in un territorio o in una struttura, per individuare gap;
- **Strumenti digitali / AI**  
  - base concettuale per progettare chatbot, assistenti digitali, triage tool e sistemi di GraphRAG che integrino davvero tutti gli attori e non solo la prospettiva clinica;
- **Advocacy e policy**  
  - supporto visuale per tavoli multi-agenzia, piani locali antiviolenza, discussione di protocolli inter-istituzionali.

---

## Contribuire

Commenti, issue e pull request sono benvenuti, in particolare su:

- adattamenti a protocolli regionali/aziendali specifici,
- integrazione di nuove evidenze scientifiche,
- miglioramenti nella leggibilità dei diagrammi,
- traduzioni in altre lingue o adattamenti per altri ordinamenti giuridici.

Se proponi modifiche basate su linee guida locali o studi specifici, ti chiediamo di:

- indicare le **fonti** (titolo, ente, anno, link se disponibile),
- segnalare se si tratta di pratica locale o di standard nazionale/internazionale.

---

## Riferimenti principali

Se usi questo lavoro in contesti accademici o professionali, puoi citare alcuni dei riferimenti su cui si basa:

- DPCM 24 novembre 2017, *Linee guida nazionali per le Aziende sanitarie e le Aziende ospedaliere in tema di soccorso e assistenza socio-sanitaria alle donne vittime di violenza*, Presidenza del Consiglio dei Ministri, pubblicato in Gazzetta Ufficiale n. 24 del 30.01.2018.

- World Health Organization, *Responding to intimate partner violence and sexual violence against women: WHO clinical and policy guidelines*, WHO, 2013.

- World Health Organization, *Health care for women subjected to intimate partner violence or sexual violence: a clinical handbook*, WHO, 2014.

- European Institute for Gender Equality (EIGE), *A guide to risk assessment and risk management of intimate partner violence against women for the police*, EIGE, 2019.

- European Institute for Gender Equality (EIGE), *Risk assessment and management of intimate partner violence in the EU*, EIGE, 2019.

- United Nations Joint Global Programme on Essential Services for Women and Girls Subject to Violence, *Essential Services Package for Women and Girls Subject to Violence – Core Elements and Guidelines for Implementation*, UN Women, UNFPA, WHO, UNDP, UNODC, 2015.  
  > Una delle persone che contribuiscono a questo repository ha lavorato direttamente al pacchetto di servizi essenziali durante la sua attività presso le Nazioni Unite (UNFPA).

- Consiglio d’Europa, *Assessing and managing risks in cases of violence against women and domestic violence*, Council of Europe, 2020 (attuazione della Convenzione di Istanbul con focus su risk assessment e risk management).

A seconda del Paese/Regione, possono inoltre essere rilevanti:

- protocolli regionali e aziendali (es. percorsi “Codice Rosa” in diversi Servizi sanitari regionali),
- piani nazionali antiviolenza aggiornati,
- linee guida dei centri antiviolenza e delle reti territoriali.

---

## Licenza

If you use this workflow in academic or professional work, please cite it as:

Marchese, G. (2025). *Workflow for multi-actor response to gender-based violence cases: a Mermaid-based process model*. GitHub repository. Available at: https://github.com/giumar11/GBV/
