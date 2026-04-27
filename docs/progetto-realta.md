# 🏠 PROGETTO — GroveO
**Il Gestionale per Ristoratori Italiani**

> Buyer Personas · Nomi Prodotto · Roadmap & Todo List
> Versione 1.0 — Marzo 2025

---

## 01 · Buyer Personas

Tre profili distinti che rappresentano il mercato target. Ognuno ha bisogni, freni e motivazioni differenti.

### Persona #1 — Mario, il Pizzaiolo Imprenditore

| | |
|---|---|
| **Età & Ruolo** | 42 anni · Proprietario di pizzeria con 2 sedi in provincia di Napoli |
| **Volume** | 60–90 coperti a sera, picco weekend. Asporto e delivery in crescita. |
| **Situazione attuale** | Registratore di cassa + WhatsApp per ordini. Excel per inventario. Nessun dato storico. |
| **Obiettivo primario** | Smettere di perdere comande e capire quali pizze rendono di più. |
| **Freni all'acquisto** | Paura del cambiamento, budget limitato, esperienza negativa con software precedente. |
| **Trigger d'acquisto** | Demo gratuita, nessun contratto, amico che mostra il sistema in diretta. |
| **Canale** | Facebook, passaparola, gruppi WhatsApp di categoria. |

> *"Quello che avevo prima non funzionava, ho speso 2.000€ e l'ho disinstallato dopo 3 mesi."*

---

### Persona #2 — Giulia, la Ristoratrice Ambiziosa

| | |
|---|---|
| **Età & Ruolo** | 36 anni · Proprietaria di ristorante fusion a Milano, aperto 2 anni fa. |
| **Volume** | 45 coperti, pranzo business + cena. Prenotazioni tramite TheFork e telefono. |
| **Situazione attuale** | TheFork + Square non integrati. Vuole un unico posto per tutto. |
| **Obiettivo primario** | Ridurre il tempo in amministrazione e capire i margini per piatto. |
| **Freni all'acquisto** | Vuole qualcosa di professionale. Teme supporto scarso post-vendita. |
| **Trigger d'acquisto** | Case study concreti, integrazione con tool esistenti, supporto chat veloce. |
| **Canale** | Instagram, LinkedIn, blog di settore, podcast per ristoratori. |

> *"Voglio qualcosa che cresce con me, non uno strumento che devo rimpiazzare tra un anno."*

---

### Persona #3 — Roberto, il Bar Manager Tecnico

| | |
|---|---|
| **Età & Ruolo** | 29 anni · Bar manager in locale di famiglia, Centro Italia. |
| **Volume** | Bar diurno + aperitivo serale. ~200 scontrini/giorno, 3 dipendenti. |
| **Situazione attuale** | È il più digitale della famiglia. Vuole il gestionale ma deve convincere il padre. |
| **Obiettivo primario** | Dimostrare che il sistema digitale porta risultati concreti e misurabili. |
| **Freni all'acquisto** | Non decide da solo. Prezzo visto come costo, non investimento. |
| **Trigger d'acquisto** | Calcolatore ROI interattivo, periodo di prova gratuito, report automatici. |
| **Canale** | YouTube, TikTok, Reddit/community tech, newsletter startup italiane. |

> *"Se riesco a mostrare a mio padre che risparmia 300€ al mese, lo convinco in 5 minuti."*

---

## 02 · Proposte di Nome

Nomi memorabili con numero simbolico integrato.

| Nome | Tagline | Numero Simbolico |
|---|---|---|
| **Tavolo80** | *"Il tuo ristorante. Finalmente in ordine."* | 80% dei ristoranti italiani senza gestionale digitale |
| **Locale360** | *"Gestisci ogni angolo del tuo locale."* | 360° di visione completa sul business |

---

## 03 · Todo List & Roadmap

Legenda priorità: 🔴 Critica · 🟡 Alta · 🟢 Media

### Sprint 0 — Fondamenta (Settimane 1–2)

| Priorità | Task | Descrizione | Owner |
|---|---|---|---|
| 🔴 | Scegliere il nome | Validare brand name con dominio + trademark check | Founder |
| 🔴 | Repo GitHub | Setup mono-repo, README, licenza MIT/AGPL | Tech Lead |
| 🔴 | Stack tecnologico | Definire stack (Next.js + Supabase? Rails?) e documentare | Tech Lead |
| 🔴 | Landing page | One-pager con value prop, waitlist e social proof | Founder + Dev |
| 🟡 | Buyer personas doc | Validare con 5 interviste a ristoratori | Founder |
| 🟡 | Competitor analysis | Deep dive su EasyPOS, Deliverect, GloriaFood, Tilby | Founder |

### Sprint 1 — MVP Core (Settimane 3–6)

| Priorità | Task | Descrizione | Owner |
|---|---|---|---|
| 🔴 | Modulo Ordini | Dashboard sala/asporto/delivery, tracking real-time | Dev |
| 🔴 | Gestione Menu | CRUD piatti, categorie, prezzi, foto | Dev |
| 🔴 | Cassa POS base | Scontrino, pagamento, chiusura giornata | Dev |
| 🔴 | Auth & multiutente | Ruoli: admin, cameriere, cuoco. Login sicuro. | Dev |
| 🟡 | KDS Cucina | Schermo cucina con code comande e priorità | Dev |
| 🟡 | Split bill | Divisione conto per coperto o prodotto | Dev |
| 🟢 | Modalità offline | Funzionamento base senza internet (PWA + cache) | Dev |

### Sprint 2 — Inventario & Personale (Settimane 7–10)

| Priorità | Task | Descrizione | Owner |
|---|---|---|---|
| 🔴 | Inventario predittivo | Scalare ingredienti da ricette collegate a vendite | Dev |
| 🔴 | Alert scorte | Notifiche push/email sotto soglia ingrediente | Dev |
| 🟡 | Turni personale | Calendario turni, permessi, sync con picchi ordini | Dev |
| 🟡 | Costo per piatto | Calcolo automatico food cost da ingredienti + ricette | Dev |
| 🟡 | Fornitori | Rubrica fornitori, ordini automatici da inventario basso | Dev |
| 🟢 | Report mensile PDF | Export automatico: coperti, revenue, food cost, errori | Dev |

### Sprint 3 — Go-to-Market (Settimane 11–14)

| Priorità | Task | Descrizione | Owner |
|---|---|---|---|
| 🔴 | Onboarding flow | Setup guidato in 30 min: menu, tavoli, personale | Product |
| 🔴 | Demo interattiva | Demo pubblica su demo.nomeapp.it con dati fittizi | Dev + Marketing |
| 🔴 | Documentazione | Docs in italiano + video tutorial YouTube | Marketing |
| 🟡 | Pilota con 3 locali | Onboarding manuale di 3 early adopter | Founder |
| 🟡 | Calcolatore ROI | Tool web: inserisci coperti → vedi risparmio | Dev |
| 🟡 | Integrazione TheFork | Import prenotazioni via API | Dev |
| 🟢 | Community Discord | Spazio per ristoratori + sviluppatori open source | Founder |
| 🟢 | Product Hunt launch | Preparare asset, testo e upvote network | Marketing |

### Backlog — Post-lancio

| Priorità | Task | Descrizione |
|---|---|---|
| 🟡 | Multi-sede | Gestione 2+ locali dallo stesso account admin |
| 🟡 | App mobile nativa | iOS + Android per camerieri e cuochi |
| 🟡 | Integrazione delivery | Glovo, Uber Eats, Just Eat — import ordini automatico |
| 🟢 | AI menu suggerimenti | Suggerimenti basati su stagionalità + scorte |
| 🟢 | Fatturazione elettronica | Export XML conforme SDI italiano |
| 🟢 | Programma fedeltà | Punti, promo personalizzate, CRM clienti base |

---

## 04 · Documentazione di Progetto

### Diario di Bordo

**05/03/2026**
- Inizio attività: definizione ruoli, responsabilità e competenze del team.
- Ore 15 (Riccardo e Thomas): avvio server Debian 13 per lavoro collaborativo condiviso.
- Gli altri componenti si documentano su [Odoo](https://www.odoo.com/it_IT) e aggiornano i ruoli.
- Obiettivo di fine giornata: setup server operativo e prima esplorazione della piattaforma.

**12/03/2026**
- Creazione logo, nome funzionale e memorabile.
- Creazione tema design della grafica Odoo.
- Configurazione iniziale: il gestionale gira nel PC principale dell'azienda (rete WiFi stabile a carico del cliente).
- Nome funzionale scelto: 🍝 **Bigoli** — funzionalità principale: **PRENDERE ORDINAZIONI**.

---

### Scadenze & Milestone

| Data | Tipo | Output richiesto |
|---|---|---|
| **10 Aprile** | Restituzione Interna | MVP base (anche solo UI su Figma/Google Sites), flussi e idea |
| **24 Aprile** | Restituzione Allargata | Presentazione a genitori e amici, formato espositivo |
| **08 Maggio** | Restituzione Esterna (Finale) | Versione Alpha con funzionalità principali, presentazione ad aziende |

> **Consegna finale: 8 maggio**
> - `08/05` = Prototipo "Iterato" / Versione Alpha
> - `24/04` = MVP presentato ai genitori
> - `10/04` = MVP (non alpha, non beta) — anche solo Figma con flussi grafici

---

### Ruoli del Team

- **Project Manager:** coordina (non decide da solo), delega i compiti, monitora l'avanzamento, fa da tramite con i docenti.
- **Responsabile Documentazione:** scrive tutto, ragiona sulle tecnologie, tiene il diario di bordo dei processi e delle decisioni.
- **Presentazione finale:** ogni membro parla con le proprie competenze tecniche specifiche.

---

## 05 · Requisiti di Sistema

### Requisiti Funzionali

- **Gestione PoS:** sistema touch per sala, asporto e domicilio; scontrini e fatturazione elettronica integrata.
- **Sync Sala-Cucina:** app mobile (tablet/smartphone) con invio diretto ai monitor KDS o stampanti di reparto.
- **Magazzino & Inventario:** scarico automatico ingredienti da distinte base piatti; alert scorte in esaurimento.
- **Prenotazioni & Tavoli:** mappa visiva del locale, turnazione tavoli, gestione caparre per eventi.
- **Menu & Pricing:** gestione centralizzata (stagionali, promozioni 2x1, happy hour) su tutti i locali.

### Requisiti Non Funzionali

- **Interfaccia intuitiva:** curva di apprendimento minima, senza rallentare il servizio.
- **All-in-One:** nessun software di terze parti, dati centralizzati in un unico database.
- **Cloud & accessibilità:** accessibile in tempo reale anche da remoto.
- **Business Intelligence:** dashboard aggiornata in real-time (costi, ricavi per piatto, storico vendite).
- **Sicurezza & GDPR:** cifratura TLS in transito, RBAC per controllo accessi, protezione dati personali clienti.

---

## 06 · Architettura del Sistema

### Flusso Logico dei Dati


graph TD
  A[Cameriere/Tablet] -- Inserimento Ordine --> B{Core Engine}
  B -- Smistamento --> C[Monitor Cucina/KDS]
  B -- Smistamento --> D[Stampante Bar]
  C -- Notifica Pronto --> A
  B -- Aggiornamento Stato --> E[Mappa Tavoli]
  E -- Richiesta Conto --> F[Modulo PoS]
  F -- Chiusura Scontrino --> G[Scarico Magazzino Automatico]
  F -- Registrazione --> H[Report Incassi Base]
```

**Livello 1 — Input (Front-end Operativo)**
1. Il cliente prenota (web/telefono) → Modulo Prenotazioni
2. Il cameriere prende l'ordine via tablet → App GroveO PoS Mobile

**Livello 2 — Elaborazione (Mid-tier)**
3. L'ordine viene diviso automaticamente: bevande al bar, cibo in cucina → KDS/Stampanti
4. Il tavolo viene segnato come "Occupato/In attesa" sulla mappa digitale

**Livello 3 — Automazione Back-end (Core ERP)**
5. All'uscita del piatto: calcolo costo e scarico ingredienti → Modulo Magazzino
6. Il cliente paga → Modulo PoS (chiusura scontrino)
7. Il pagamento genera una registrazione → Modulo Contabilità

**Livello 4 — Output & Analisi (Management)**
8. Dati serata (tempi, piatti, incasso, sprechi) → Dashboard/Analytics KPI

---

## 07 · Gantt — Timeline Implementazione

Durata stimata per la transizione completa di 1 locale standard: **6 Settimane**

| Settimana | Fase | Attività | Output/Milestone |
|---|---|---|---|
| **Sett. 1** | Setup IT & Sicurezza | Server protetto, DB con backup/cifratura, deploy GroveO, test vulnerabilità | Server operativo e app online |
| **Sett. 2** | Analisi & Data Entry | Mappatura tavoli, inserimento menu, distinte base, inventario iniziale | Struttura creata e DB popolato |
| **Sett. 3** | Configurazione Moduli | Setup PoS, Magazzino, HR turni, Contabilità base, definizione RBAC | Sistema lato software pronto |
| **Sett. 4** | Hardware & Integrazione | Installazione tablet, KDS, stampanti, stress test | Hardware di rete integrato |
| **Sett. 5** | Formazione Personale | Training titolare (admin/dashboard) e dipendenti (comande, cassa, privacy) | Personale autonomo |
| **Sett. 6** | Go-Live & Supporto | Avvio produzione con presenza tecnica in loco | **Progetto Chiuso** |

---

## 08 · Sprint Planning (Agile Fast-Track)

| Sprint | Focus | Priorità | Task Principali |
|---|---|---|---|
| **Sprint 1** | Backend & Core Logics | Alta | Setup DB, API inserimento ordine, logica smistamento comande |
| **Sprint 2** | Interfaccia Operativa | Alta | UI tablet (UX veloce), mappa tavoli, schermata KDS cucina |
| **Sprint 3** | Chiusura & Analisi | Media | Modulo pagamenti, scarico magazzino, dashboard KPI base |

---

## 09 · Funzionalità Core MVP

1. **Presa Comande Rapida** — interfaccia touch con categorie e varianti (es. "senza cipolla")
2. **Mappa Tavoli Dinamica** — stati: Libero, Occupato, In attesa, Conto
3. **Routing Ordini** — separazione automatica tra Cucina e Bar
4. **Chiusura Transazione** — scontrino e pagamento (contanti/POS)
5. **Scarico Ingredienti** — decurtazione automatica quantità ad ogni vendita

---

## 10 · Stack Tecnologico Consigliato

| Layer | Tecnologia |
|---|---|
| **Frontend** | React o Flutter (fluidità su tablet) |
| **Backend** | Node.js o Python (FastAPI) — real-time |
| **Database** | PostgreSQL (consistenza dati finanziari) |
| **Sicurezza** | JWT per sessioni + TLS per comunicazione tablet-server |
| **Infrastruttura** | Docker per deploy rapido e scalabile |

### Tabelle DB Fondamentali (Sprint 1)

```sql
tables   (id, status, current_order_id)
products (id, name, price, department, stock_quantity)
orders   (id, table_id, total, status, created_at)
```

---

## 11 · Sicurezza

1. **Autenticazione:** JWT con scadenza breve (es. 4 ore) prima di accedere alla Mappa Tavoli.
2. **Comunicazione:** tutte le richieste tablet → backend forzate su HTTPS (TLS 1.3).
3. **Autorizzazione RBAC:** il campo `department` nel payload JSON determina i permessi. Il barista non vede gli ordini della cucina.
4. **Audit Log:** ogni azione (ordine, modifica, annullamento, sconto) registrata nella tabella `audit_logs` in PostgreSQL.

---

## 12 · Script Pitch Deck — GroveO

### Introduzione & Problema (Marco)
- **Slide 1 — Copertina:** *"Ciao a tutti. Presentiamo GroveO: il nostro gestionale per ristoranti progettato per essere naturale, connesso e vivo."*
- **Slide 2 — Il Caos Attuale:** *"Oggi il settore soffre di una vera 'frattura' operativa. Le casse sono isolate, non esiste controllo dei margini in real-time e la lentezza nelle comande causa stress e perdite costanti."*

### Target & Soluzione (Edoardo)
- **Slide 3 — I Nostri Clienti:** Locali con flusso medio-alto: pizzerie, ristoranti, bar. Servono ordini veloci, meno errori sala-cucina e controllo costi materie prime.
- **Slide 4 — La Soluzione:** *"GroveO ottimizza i tempi di servizio e riduce gli errori operativi. Sistema completamente connesso, scalabile dal singolo ristorante a catene multi-sede tramite moduli Odoo."*

### Flusso Dati & Robustezza (Buffo)
- **Slide 5 — Flusso Dati Real-Time:** Il sistema ottimizza il dato in 3 fasi: inserimento touch immediato → routing automatico → analisi finale.

---

## 13 · Digital Marketing — Linee Guida Presentazione

### Struttura Narrativa Consigliata
- **Persuasiva:** Intro (chi/cosa) → Problema (bisogni) → Soluzione (prodotto) → Esecuzione (processo, timeline, budget, team) → Risultato (proiezione)
- **Esplicativa:** Contesto → Chi/Cosa → Informazioni + dati → Conclusione (impatto)

### Regole Visive
- Usare **infografiche e grafici** al posto del testo denso
- Meno parole sulle slide → vengono raccontate a voce
- Parole chiave evidenziate, non frasi intere