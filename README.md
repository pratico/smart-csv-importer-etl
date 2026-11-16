# Smart CSV Importer — High-Throughput Streaming ETL & File Sanitizer (CSV / XML / JSON)

🇬🇧 / 🇺🇸 **ENGLISH** | [🇮🇹 Vai alla versione in Italiano](#-italiano)

[![Portfolio](https://img.shields.io/badge/Portfolio-antoniangeloflore.com-0d6efd?style=flat-square)](https://antoniangeloflore.com)
[![Stack](https://img.shields.io/badge/Stack-Node.js%20%7C%20Express%20%7C%20MySQL%20%7C%20Streaming%20ETL-198754?style=flat-square)](https://github.com/pratico)
[![Privacy](https://img.shields.io/badge/Privacy-Isolated%20Local%20Execution%20%2F%20GDPR%20Safe-dc3545?style=flat-square)](https://antoniangeloflore.com)

## Product Overview

**Smart CSV Importer** is a high-throughput, local-first ETL and **File Sanitizer** engine engineered to validate, clean, deduplicate, convert, and enrich large supplier product catalogs (**10,000 to 500,000+ rows**) across **CSV, XML, and JSON** formats.

Operated exclusively inside a private, isolated Linux workstation environment, this software powers an **asynchronous B2B data-sanitization and catalog-enrichment pipeline** for **e-commerce teams, catalog managers, web agencies, and SMEs**—eliminating manual spreadsheet work while guaranteeing strict **GDPR and NDA data isolation**.

## The Problem Solved

E-commerce operations and web agencies dealing with multi-supplier feeds face recurring, expensive bottlenecks:

- **Hours wasted on manual cleanup:** Fixing broken encodings, inconsistent delimiters, and mismatched columns across heterogeneous supplier files consumes entire engineering days.
- **Silent formatting errors:** Prices using commas instead of dots, malformed numbers, broken XML/JSON tags, and missing mandatory attributes corrupt store imports and cause pricing errors.
- **Catalog pollution from duplicates:** Repeated SKUs or slightly altered product codes create duplicate listings that confuse buyers and sales teams.
- **GDPR & NDA compliance risks:** Uploading proprietary supplier price lists or internal catalogs into unverified public cloud SaaS tools or public AI interfaces exposes confidential business data.

**Smart CSV Importer** turns fragile, messy supplier feeds into deterministic, production-ready datasets ready for Shopify, WooCommerce, Magento, PrestaShop, or custom ERPs.

## Operator Workflow (Isolated Local Pipeline)

The pipeline is executed locally in an isolated environment to ensure maximum speed, zero memory exhaustion, and total data confidentiality:

1. **Raw Feed Ingestion:** The raw supplier file (**CSV, XML, or JSON**) is loaded directly into the local engine without manual pre-processing.
2. **Pre-Import Schema & Data Preview:** Before any transformation or database write occurs, the engine parses the structure and displays an immediate preview to verify column mapping and encoding.
3. **Streaming Validation & File Sanitizer Mode:** Every row is processed via Node.js streams—catching malformed prices, missing fields, and encoding anomalies—and can be exported directly as a sanitized file without requiring an external database.
4. **Workspace Isolation & Automated Deduplication:** Multi-supplier imports are isolated into dedicated **Workspaces**, automatically detecting and removing duplicate SKUs before export.
5. **Optional AI SEO Enrichment & Localization:** When requested, product descriptions are enriched with clean HTML SEO copy and multi-language translations under strict privacy controls.
6. **Production-Ready Delivery:** The final output is exported as a clean, normalized CSV, XML, or JSON file ready for immediate e-commerce or ERP ingestion.

## Core Capabilities & Business ROI

* **Multi-Format Streaming Engine (CSV, XML, JSON):** Handles 10,000 to 500,000+ rows smoothly without memory bottlenecks, cutting catalog preparation from hours to minutes.
* **Standalone File Sanitizer Mode:** Cleans, normalizes, and converts broken supplier feeds directly into valid output files without database overhead.
* **Workspace Isolation:** Keeps different client projects and supplier catalogs completely separated with zero cross-contamination.
* **Deterministic Error Interception:** Catches malformed prices, broken characters, and missing fields before they reach production stores—preventing costly pricing mistakes.
* **Automated SKU Deduplication:** Eliminates duplicate records automatically for clean, reliable product catalogs.
* **100% Local & Private Execution:** Operated on an isolated local Linux environment—proprietary supplier price lists never leave controlled infrastructure.

**Immediate ROI:** For an e-commerce team or agency updating supplier catalogs weekly, outsourcing messy feed sanitization eliminates dozens of hours of repetitive manual work per month with zero software setup, zero subscriptions, and zero risk of catalog corruption.

## High-Level Architecture & Stack

* **Node.js & Express (Streaming I/O):** Event-driven architecture utilizing Node.js streams for constant, low-memory throughput on large files.
* **MySQL:** Transactional relational storage powering isolated Workspaces, deduplication indexing, and auditability.
* **Bootstrap 5 & EJS:** Clean, responsive operator control interface for rapid inspection, validation, and export.
* **Linux Native Environment:** Hardened local execution ensuring full data sovereignty and predictable performance.

## Requirements

* **Linux** Operating System
* **Node.js 18+** & **MySQL 8+**

## Confidentiality Notice & Free 50-Row B2B Test

🔒 **Proprietary Software Asset (All Rights Reserved):** This repository serves as a functional and architectural showcase within the Professional Portfolio ([https://antoniangeloflore.com](https://antoniangeloflore.com) — *Italian portal & video demos; English B2B delivery*). Operated privately in an isolated local environment to protect client confidentiality and NDA compliance, the source code is not publicly exposed.

🧪 **Free 50-Row Sample Evaluation (Zero-Call B2B Service):** Have a messy 10,000+ row CSV, XML, or JSON supplier feed that needs cleaning, schema normalization, or AI SEO descriptions? Send a **50-row sample** via [antoniangeloflore.com](https://antoniangeloflore.com) or [LinkedIn](https://www.linkedin.com/in/antoniangelo-f-30003622/). and receive a cleaned, production-ready file within 24 hours—completely free.

---

<a name="-italiano"></a>
## 🇮🇹 ITALIANO

# Smart CSV Importer — Motore ETL Streaming ad Alte Prestazioni & File Sanitizer (CSV / XML / JSON)

## Panoramica del Prodotto

**Smart CSV Importer** è un motore ETL e **File Sanitizer** ad alte prestazioni progettato per validare, bonificare, deduplicare, convertire e arricchire listini prodotti di grandi dimensioni (**da 10.000 fino a oltre 500.000 righe**) nei formati **CSV, XML e JSON**.

Eseguito esclusivamente in un ambiente Linux locale isolato, questo software alimenta una **pipeline B2B asincrona di bonifica dati e arricchimento cataloghi** dedicata a **e-commerce, catalog manager, web agency e PMI** — eliminando il lavoro manuale sui fogli di calcolo e garantendo il massimo rispetto di **GDPR e accordi di riservatezza (NDA)**.

## Il Problema Risolto

Chi gestisce listini multi-fornitore per e-commerce e web agency affronta ogni settimana colli di bottiglia costosi e ripetitivi:

- **Ore perse in pulizia manuale:** correggere encoding corrotti, separatori incoerenti e colonne disallineate su file eterogenei consuma intere giornate operative.
- **Errori di formato silenziosi:** prezzi con virgole al posto dei punti, quantità malformate, tag XML/JSON rotti e campi obbligatori mancanti generano importazioni fallite o prezzi errati online.
- **Duplicati che inquinano il catalogo:** lo stesso prodotto importato più volte o con codici leggermente diversi crea doppioni che danneggiano vendite e indicizzazione.
- **Rischi GDPR e riservatezza listini:** caricare listini prezzi riservati dei fornitori su strumenti cloud non verificati o AI pubbliche espone dati aziendali sensibili a terze parti.

**Smart CSV Importer** trasforma tracciati fornitori sporchi e fragili in file deterministici pronti per l'importazione immediata su Shopify, WooCommerce, Magento, PrestaShop o ERP aziendali.

## Flusso Operativo (Pipeline Locale Isolata)

La lavorazione viene eseguita interamente in ambiente locale isolato per assicurare velocità massima, zero saturazione di memoria e totale riservatezza dei dati:

1. **Acquisizione Tracciato Grezzo:** il listino del fornitore (**CSV, XML o JSON**) viene caricato direttamente nel motore locale senza alcuna pre-elaborazione manuale.
2. **Anteprima Schema e Dati:** prima di qualsiasi trasformazione o scrittura su database, il sistema analizza la struttura e mostra un'anteprima immediata per verificare mappatura delle colonne ed encoding.
3. **Validazione Streaming & Modalità File Sanitizer:** ogni riga viene elaborata tramite stream Node.js — intercettando prezzi malformati, campi mancanti e anomalie di codifica — con possibilità di esportare direttamente il file bonificato senza obbligo di database.
4. **Isolamento Workspace & Deduplicazione Automatica:** le lavorazioni di diversi fornitori o clienti sono isolate in **Workspace dedicati**, individuando ed eliminando automaticamente gli SKU duplicati.
5. **Arricchimento SEO AI & Traduzioni (Opzionale):** su richiesta, le schede prodotto vengono arricchite con descrizioni HTML ottimizzate SEO e traduzioni multilingua in ambiente controllato.
6. **Consegna Pronta per la Produzione:** il risultato finale viene esportato in un file CSV, XML o JSON pulito, normalizzato e pronto per il caricamento immediato sull'e-commerce o sull'ERP.

## Funzionalità Principali & Vantaggi Operativi (ROI)

* **Motore Streaming Multi-Formato (CSV, XML, JSON):** elabora da 10.000 a oltre 500.000 righe senza blocchi di memoria, riducendo la preparazione dei cataloghi da ore a pochi minuti.
* **Modalità File Sanitizer Standalone:** bonifica, normalizza e converte tracciati fornitori corrotti direttamente in file validi pronti all'uso.
* **Isolamento tramite Workspace:** mantiene separati i cataloghi di clienti e fornitori diversi evitando qualsiasi contaminazione dei dati.
* **Intercettazione Deterministica degli Errori:** blocca prezzi errati, caratteri corrotti e campi vuoti prima che finiscano online, azzerando reclami ed errori di listino.
* **Deduplicazione Automatica SKU:** rimuove i prodotti duplicati garantendo cataloghi coerenti e affidabili.
* **Esecuzione 100% Locale e Riservata:** operato su infrastruttura Linux locale isolata — i listini riservati non vengono mai esposti a servizi cloud esterni.

**ROI immediato:** per un e-commerce o una web agency che aggiorna listini settimanalmente, delegare la bonifica dei tracciati sporchi recupera decine di ore di lavoro manuale al mese senza costi di licenza, senza configurazioni e senza rischi per il catalogo.

## Tecnologie Utilizzate (Ad Alto Livello)

* **Node.js & Express (Streaming I/O):** architettura event-driven basata su stream per elaborare grandi volumi di dati con consumo di memoria costante.
* **MySQL:** database relazionale transazionale a supporto dei Workspace isolati, dell'indicizzazione anti-duplicati e della tracciabilità.
* **Bootstrap 5 & EJS:** interfaccia operativa pulita e reattiva per ispezione rapida, validazione ed esportazione.
* **Ambiente Nativo Linux:** esecuzione locale controllata per garantire sovranità del dato e stabilità operativa.

## Requisiti

* Sistema operativo **Linux**
* **Node.js 18+** & **MySQL 8+**

## Nota di Riservatezza & Test Gratuito su 50 Righe

🔒 **Asset Software Proprietario (Tutti i diritti riservati):** Questo repository ha finalità di presentazione funzionale e architetturale per il Portfolio Professionale ([https://antoniangeloflore.com](https://antoniangeloflore.com)). Operato privatamente in ambiente locale isolato a tutela della riservatezza e degli accordi NDA, il codice sorgente non è esposto pubblicamente.

🧪 **Prova Gratuita su Campione da 50 Righe (Servizio B2B Asincrono Zero-Call):** Hai un listino fornitori CSV, XML o JSON da 10.000+ righe da bonificare, convertire o arricchire con descrizioni SEO? Invia un **campione di 50 righe** tramite [antoniangeloflore.com](https://antoniangeloflore.com) o [LinkedIn](https://www.linkedin.com/in/antoniangelo-f-30003622/). e ricevi il file pulito e pronto per l'importazione entro 24 ore, gratuitamente.
