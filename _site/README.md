# eric-falegname-genova.github.io

Sito web professionale per falegname artigiano a Genova. Portfolio mobili su misura e strutture letti giapponesi. Built with Jekyll & GitHub Pages.

## 📋 Informazioni sul Progetto

Sito vetrina per Eric, falegname artigiano con oltre 10 anni di esperienza (dal 2018). Originario di Sant'Stefano in Roero, opera nella zona di Genova offrendo servizi a domicilio.

### Servizi Principali
- Mobili su misura
- Strutture rialzate per letti tradizionali giapponesi (Futon)
- Restauro e recupero mobili
- Interventi a domicilio

## 🛠️ Tecnologie Utilizzate

- **Jekyll 4.3+** - Generatore di siti statici
- **GitHub Pages** - Hosting gratuito
- **Liquid** - Template engine
- **Markdown** - Formato contenuti
- **Schema.org JSON-LD** - SEO locale ottimizzato

## 📁 Struttura del Progetto

```
eric-falegname-genova.github.io/
├── _config.yml # Configurazione Jekyll
├── index.md # Homepage
├── contatti.md # Pagina contatti
├── portfolio-tradizionale.md # Pagina portfolio classico
├── portfolio-giapponese.md # Pagina letti giapponesi
├── _layouts/ # Template HTML
├── _includes/ # Componenti riutilizzabili
│ └── seo-schema.html # Schema.org per Local SEO
├── _portfolio_tradizionale/ # Collection: progetti classici
│ └── [progetto].md # File singoli progetti
├── _portfolio_giapponese/ # Collection: letti giapponesi
│ └── [progetto].md # File singoli progetti
└── assets/
├── css/ # Fogli di stile
└── images/ # Immagini e foto portfolio
```


## 🚀 Installazione e Setup Locale

### Prerequisiti

- Ruby 3.1.4+ (installato tramite rbenv o rvm)
- Bundler (`gem install bundler`)
- Git

### Clonazione e Setup

```bash
# Clona la repository
git clone https://github.com/emanuelePepeUAS/eric-falegname-genova.github.io.git
cd eric-falegname-genova.github.io

# Installa le dipendenze
bundle install

# Avvia il server locale
bundle exec jekyll serve

# Apri il browser su http://localhost:4000
```

## Build per Produzione

```bash
bundle exec jekyll build
```

I file pronti per il deploy saranno nella cartella _site/.


## 📝 Come Aggiungere Contenuti

Aggiungere un Nuovo Progetto al Portfolio
1. Crea un nuovo file nella cartella appropriata:

_portfolio_tradizionale/nome-progetto.md

_portfolio_giapponese/nome-progetto.md

2. Usa questo template:

```text
***
layout: project
title: "Nome del Progetto"
date: 2025-01-15
image: /assets/images/portfolio/progetto-nome.jpg
category: mobili-su-misura
***

Descrizione dettagliata del progetto, materiali utilizzati, dimensioni, ecc.

## Dettagli Tecnici
- **Legno:** Rovere massello
- **Dimensioni:** 200x180x40 cm
- **Tempo realizzazione:** 3 settimane
```

3. Carica l'immagine corrispondente in assets/images/portfolio/


Modificare i Contatti
Edita il file contatti.md e aggiorna:

Numero di telefono/WhatsApp

Email

Eventuali social media

Aggiornare Informazioni SEO
Nel file _config.yml, modifica:

title, description, email

Social media handles

Indirizzo e coordinate geografiche

Nel file _includes/seo-schema.html, aggiorna:

telephone

address (se necessario precisare via/numero civico)

openingHours (orari di disponibilità)

🔍 SEO e Indicizzazione
Local Business Schema
Il sito include markup Schema.org per la SEO locale, ottimizzato per ricerche come:

"falegname Genova"

"mobili su misura Genova"

"letti giapponesi Genova"

Google Business Profile
Per massimizzare la visibilità:

Registra Eric su Google Business Profile

Collega questo sito come sito web ufficiale

Mantieni coerenti le informazioni (NAP: Name, Address, Phone)

🎨 Personalizzazione Stile
Font
Il sito usa Young Serif per i titoli (stile rustico-artigianale) e system fonts per il corpo del testo.

Colori Consigliati (da implementare in CSS)
Primario: #8B4513 (marrone legno)

Secondario: #2F4F4F (ardesia scuro)

Accenti: #D2691E (cioccolato)

Background: #FFF8DC (cornsilk)

📄 Licenza
Codice sorgente: MIT License - Puoi riutilizzare e modificare il codice

Contenuti (testi, immagini, progetti): © Eric [Cognome] - Tutti i diritti riservati. Non possono essere utilizzati senza autorizzazione.

🤝 Contributi
Questo è un sito privato per un'attività commerciale. Per modifiche o suggerimenti, contatta direttamente il maintainer.

📧 Contatti Sviluppatore
Per questioni tecniche relative al sito, contatta [tua-email@esempio.com]

Ultimo aggiornamento: Febbraio 2026
Status: 🚧 In sviluppo


"The source code is licensed under MIT. The content (images, text, and project details) is © Eric [Cognome] and cannot be used without permission."
