# VibeWhisper

> Idee che diventano codice

**VibeWhisper** è il portfolio showcase di **44 progetti** raccolti in **9 sezioni tematiche** — dal mondo dei PDF agli EPUB, dalla traduzione di documenti ai diagrammi Mermaid, dal cloud storage al batch renaming, dalla dettatura vocale all'analisi forex, fino ai database relazionali. Ogni progetto risolve un problema reale con un'interfaccia pensata per chi la usa.

## 🚀 Guarda lo Showcase

Apri [`showcase/index.html`](showcase/index.html) nel browser oppure visita il sito live su Cloudflare: [vibewhisper.vigliafg.workers.dev](https://vibewhisper.vigliafg.workers.dev/).

## 🗺️ Le Sezioni

La home è un hub: ogni sezione raccoglie i progetti per **tipo di lavoro**.

| Sezione | Progetti | Cosa contiene |
|---|---|---|
| [🧭 Noesis](showcase/noesis.html) | 14 | Reader, traduzione EPUB/PDF, cloner, engine, EPUB tools, Excalidraw, Roads, sito |
| [📄 Documenti & PDF](showcase/documenti.html) | 6 | pdfhandler, pdfhandler-ng, pdfextractor, pdfshow, Pandoc WASM Studio, Book Consultant |
| [📚 EPUB & libri](showcase/epub-libri.html) | 6 | EPUB Studio (v0.1.0, desktop multipiattaforma), IBS Metadata Scraper, epub2site, epubsplitter, epubslimer, fscalibre |
| [🌍 Lingua & voce](showcase/lingua-voce.html) | 3 | mdtranslator, cli_translator, NovoDictate |
| [📈 Finanza](showcase/finanza.html) | 4 | ForexFlow AI, ForexVision, ForexSMC, FX Trading Analyst |
| [📊 Statistica](showcase/statistica.html) | 4 | LazStats JS, LazStats Pro (v0.35.0, CLI e MCP), RcmdrShiny (v1.13.0), RcmdrShiny Studio (v3.2.0) |
| [🧩 Diagrammi & AI](showcase/diagrammi-ai.html) | 2 | Mermaid Creator, mermaid-to-excalidraw |
| [🗂️ File, cloud & sicurezza](showcase/file-cloud-sicurezza.html) | 3 | Bulk Renamer PRO, Cyfer, TGM Drive NXT |
| [🗄️ Database](showcase/database.html) | 2 | adbx-legacy (v0.10.0, Windows/macOS/Linux), dBX (v0.10.0, Python/PyQt6, wheel e bundle multipiattaforma) |

La sezione **Noesis** ha una mappa dedicata che classifica i 14 repository in 6 famiglie. La tabella qui sotto elenca le **schede con pagina di dettaglio**; gli altri repository Noesis sono raggiungibili dalla mappa.

## 🧩 I Progetti

| Progetto | Descrizione | Stack |
|---|---|---|
| 📚 [Noesis Reader](showcase/noesis-reader.html) | Reader EPUB con traduzione in tempo reale, appunti, editor ed Excalidraw | Vanilla JS, EPUB Reader, Offline-first |
| 📄 [pdfhandler](showcase/pdfhandler.html) | Toolbox PDF client-side: 15+ strumenti, zero upload | React 19, TypeScript, Tailwind |
| 📱 [pdfhandler-ng](showcase/pdfhandler-ng.html) | Variante mobile-first di pdfhandler: 20 strumenti PDF | React 19, TypeScript 6, Tailwind 4 |
| 📊 [IBS EPUB Metadata Scraper](showcase/ibs-epub-metadata-scraper.html) | Arricchisci EPUB con metadati da IBS.it | Python, CLI + GUI, Web Scraping |
| 🌐 [epub2site](showcase/epub2site.html) | Converti EPUB in sito web statico leggibile ovunque | Node.js, CLI |
| ☁️ [TGM Drive NXT](showcase/tgm-drive-nxt.html) | Cloud personale via Telegram: upload fino a 2 GB | Python, PyQt6, Telegram API |
| 📖 [EPUB Studio](showcase/epub-studio.html) | Lettore, editor e toolkit EPUB desktop con interfaccia Acrobat, motore Calibre incluso e installer per Linux, macOS e Windows. Release 0.1.0 | Electron, React 19, TypeScript, epub.js, CodeMirror 6 |
| ✂️ [epubsplitter](showcase/epubsplitter.html) | Estrai capitoli EPUB in nuovi file autonomi | React + TS, JSZip |
| 🗜️ [epubslimer](showcase/epubslimer.html) | Comprimi immagini EPUB con Canvas API | React + TS, JSZip |
| 📑 [pdfextractor](showcase/pdfextractor.html) | Converti PDF scientifici in Markdown pulito | Python, Docling, CLI |
| 🌍 [mdtranslator](showcase/mdtranslator.html) | Traduci Markdown preservando la formattazione | Python, CLI + GUI, Tkinter |
| 📖 [cli_translator](showcase/cli_translator.html) | Traduci EPUB con Google o AI via OpenRouter | Python, CLI, ebooklib |
| 📚 [Noesis Ebook Translator](showcase/noesis-ebook-translator.html) | Traduci EPUB preservando formattazione e indice | Python, PyQt6, foliate-js, LLM |
| ⌨️ [Noesis Ebook Translator Engine](showcase/noesis-ebook-translator-engine.html) | Lo stesso motore EPUB in CLI, TUI e server MCP per agenti, senza Qt | Python, CLI, Textual, MCP |
| 🌍 [Noesis PDF Cloner](showcase/noesis-pdf-cloner.html) | PDF originale e clone tradotto affiancati; scansioni via Mistral OCR → Markdown tradotto, viewer Markdown ed export PDF/MD. Release 0.2.2 | Python, PyQt6, pdf2zh_next, BabelDOC, Mistral OCR |
| 🐳 [Noesis PDF Cloner Service](showcase/noesis-pdf-cloner-service.html) | Server web e CLI per PDF tradotti; scansioni OCR → Markdown + PDF hardcopy. Release 0.2.2 | FastAPI, Docker, pdf2zh_next, Mistral OCR |
| 🔎 [Noesis PDF Reader Lite](showcase/noesis-pdf-reader-lite.html) | PDF → Markdown con engine adattativo dei fix | Python, PyQt6, PyMuPDF4LLM |
| 🧾 [Noesis PDF Reader Lite Engine](showcase/noesis-pdf-reader-lite-engine.html) | Estrazione e traduzione PDF da riga di comando | Python, CLI, OCR, pandoc |
| 🎨 [Noesis Roads](showcase/noesis-roads.html) | Schede didattiche d'arte dettaglio per dettaglio | React, Node.js, SQLite, AI |
| 🧜 [Mermaid Creator](showcase/mermaid-creator.html) | Diagrammi Mermaid con l'AI e workspace affiancato | Tauri 2, React 19, Rust, SQLite |
| 🧩 [mermaid-to-excalidraw](showcase/mermaid-to-excalidraw.html) | 22 tipi Mermaid in elementi Excalidraw editabili | TypeScript, Mermaid 12, Excalidraw |
| ✏️ [Bulk Renamer PRO](showcase/bulkrenamer.html) | Rinomina file in batch con 17 regole | Python, PyQt6 |
| 🎙️ [NovoDictate](showcase/novodictate.html) | Dettatura italiana con Faster-Whisper e LanguageTool | Python, PyQt6, Whisper, VAD |
| 🔐 [Cyfer](showcase/cyfer.html) | Cifratura file con GUI moderna: AES, DES, 3DES | Python, CustomTkinter, Crittografia |
| 🖼️ [pdfshow](showcase/pdfshow.html) | Galleria visiva di copertine PDF con cache intelligente | Python, Streamlit, PyMuPDF |
| 📊 [ForexFlow AI](showcase/forexflow.html) | Analisi tecnica EUR/USD con 9 modelli previsionali e AI | React 19, TypeScript, Vite, OpenRouter, NVIDIA NIM |
| 📈 [ForexVision](showcase/forexvision.html) | Tecnica, SMC e sentiment in un unico verdetto | Vanilla JS, Canvas, Yahoo Finance |
| 📈 [ForexSMC](showcase/forexsmc.html) | Analizzatore SMC/ICT per EUR/USD, GBP/USD e USD/JPY | HTML, Vanilla JS, Python |
| 📝 [Book Consultant](showcase/book-consultant.html) | Assistente desktop per scrivere libri: editor a sezioni, cinque personalità AI che propongono, versioning live, Second Brain, figure generate ed export in cinque formati. Release 1.0.0, 455 test | Python, Flet 1.1.4, SQLite, OpenRouter |
| 🔎 [fscalibre](showcase/fscalibre.html) | Ricerca fuzzy nella libreria Calibre: titolo, autore, descrizione e tag in AND, soglia regolabile, TUI Textual e GUI Flet sullo stesso motore | Python, Textual, Flet, rapidfuzz |
| 📉 [FX Trading Analyst](showcase/fx-trading-analyst.html) | Briefing FX giornaliero con SMC e analisi tecnico-statistica sugli stessi candle, più sentiment, analoghi, dibattito e scorecard. Solo stdlib | Python, Claude Code Skill, Bootstrap |
| 📊 [LazStats JS](showcase/lazstatjs.html) | Statistica inferenziale nel browser, 100% client-side | React 19, TypeScript, Victory |
| ⚡ [LazStats Pro](showcase/lazstatjs-pro.html) | Evoluzione desktop, CLI e MCP: oltre 70 procedure, report e agenti AI. Release 0.35.0 | Electron, React 19, TypeScript, Vega-Lite, MCP |
| 📊 [RcmdrShiny](showcase/rstats-commander.html) | R Commander ricostruito su Shiny, senza Tcl/Tk: 213 dialoghi, 863 voci di menu, R Markdown e knitr. Release 1.13.0 | R, Shiny, bslib, DT, rhandsontable |
| 🎛️ [RcmdrShiny Studio](showcase/rcmdr-studio.html) | Workbench statistico browser-native ispirato a R Commander: command palette, Chart Studio ggplot2, progetti e Plugin SDK. Release 3.2.0 | R, Shiny, ggplot2, plotly, DT |
| 🔄 [Pandoc WASM Studio](showcase/pandoc-wasm-studio.html) | Convertitore universale di documenti nel browser | React 19, TypeScript, WebAssembly |
| 🗄️ [adbx-legacy](showcase/adbx-legacy.html) | Clone di Alpha Four v3 su griglia 80×25: SQLite, DBF, regole, set, report, script. Release 0.10.0 con installer Windows NSIS, .dmg macOS, .deb e AppImage Linux | Python, PyQt6, SQLite |
| 🧮 [dBX](showcase/dbasex.html) | Personal database in stile dBASE 5.5: Table Builder, Query Designer con QBE, form, report, etichette, MiniScript e validazione dei campi. Versione 0.10.0, 584 test, wheel e bundle Linux/Windows/macOS | Python, PyQt6, SQLite |

## 🛠️ Tecnologie

- **Frontend**: Vanilla JS, React 19 + TypeScript, Tailwind CSS, Electron, epub.js, CodeMirror 6
- **Backend/CLI**: Python, Node.js, FastAPI, Docker
- **Desktop GUI**: PyQt6, Flet, Tauri 2 + Rust, Tkinter, CustomTkinter, Textual
- **API/AI**: Google Translate, DeepL, Microsoft/Bing, OpenRouter, Gemini, Telegram Bot API, Yahoo Finance, Claude Code
- **Formati**: EPUB, PDF, Markdown, HTML/CSS, DOCX, LaTeX, Mermaid, SVG/PNG
- **Dati e motori**: SQLite, PyMuPDF, PyMuPDF4LLM, pdf2zh_next/BabelDOC, Pandoc WASM
- **Statistica e R**: jStat, Victory, R 4.1+, Shiny, ggplot2, plotly, RcmdrMisc

## 📁 Struttura

```
VibeWhisper/
├── showcase/
│   ├── index.html          # Home hub con le 9 sezioni
│   ├── styles.css          # Design system condiviso
│   ├── noesis.html         # Mappa dell'ecosistema Noesis
│   ├── documenti.html      # Sezione Documenti & PDF
│   ├── epub-libri.html     # Sezione EPUB & libri
│   ├── lingua-voce.html    # Sezione Lingua & voce
│   ├── finanza.html        # Sezione Finanza
│   ├── statistica.html     # Sezione Statistica
│   ├── diagrammi-ai.html   # Sezione Diagrammi & AI
│   ├── file-cloud-sicurezza.html  # Sezione File, cloud & sicurezza
│   ├── database.html       # Sezione Database
│   ├── epub-studio.html    # Scheda EPUB Studio
│   ├── adbx-legacy.html    # Scheda adbx-legacy
│   ├── dbasex.html         # Scheda dBX
│   └── *.html              # Pagine dettaglio per ogni progetto
├── .agents/                # Codebuff skill config
└── skills-lock.json
```

## 📄 Licenza

MIT — vedi i repository dei singoli progetti per i dettagli.
