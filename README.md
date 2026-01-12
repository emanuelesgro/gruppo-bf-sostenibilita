# Gruppo BF - Progetto Sostenibilità

Pagina web informativa sull'impegno del Gruppo BF SpA per la sostenibilità ambientale, sociale ed economica nel settore agricolo italiano.

## 📋 Descrizione Progetto

Questo progetto è stato sviluppato come Project Work per per presentare le principali attività di sostenibilità del Gruppo BF, azienda leader nel settore primario agricolo italiano.

La pagina web fornisce:
- Panoramica del Piano Strategico di Sostenibilità 2023-2027
- I 5 pilastri strategici della sostenibilità
- Risultati concreti raggiunti nel 2023
- Certificazioni e standard di qualità
- Download del report di sostenibilità completo

##  Contenuti Principali

### I 5 Pilastri della Sostenibilità BF:

1. **Sostenibilità Ambientale** - Riduzione emissioni CO₂, energie rinnovabili, agricoltura di precisione
2. **Biodiversità** - Protezione ecosistemi, 10% terreni dedicati alla biodiversità
3. **Tracciabilità di Filiera** - Certificazioni qualità, codice condotta fornitori
4. **Capitale Umano** - Valorizzazione risorse umane, formazione, sicurezza
5. **Comunità e Territorio** - Progetti sociali, valorizzazione patrimonio locale

### Dati Chiave 2023:
- 1.220 ettari dedicati a iniziative di biodiversità
- 4.237 kWp di impianti fotovoltaici installati
- 30+ certificazioni internazionali (ISO 14001, ISO 45001, IFS, ISCC EU, ecc.)
- 74% dei fornitori rilevanti ha adottato il Codice di Condotta

##  Come Usare il Progetto

### Visualizzazione Locale

1. **Clona il repository:**
   ```bash
   git clone https://github.com/[tuo-username]/gruppo-bf-sostenibilita.git
   cd gruppo-bf-sostenibilita
   ```

2. **Apri il file HTML:**
   - Doppio click su `gruppo-bf-sostenibilita.html`
   - Oppure apri con il browser 

3. **Nessun server necessario:**
   - Il progetto è completamente statico
   - Non richiede dipendenze o installazioni

### Deploy su GitHub Pages

1. **Accedi al sito:**
   [- il sito e' disponibile a:
   - `https://[tuo-username].github.io/gruppo-bf-sostenibilita/`](https://emanuelesgro.github.io/gruppo-bf-sostenibilita/Untitled-1.html)


##  Struttura File

```
gruppo-bf-sostenibilita/
│
├── gruppo-bf-sostenibilita.html    # Pagina web principale
├── 9.gruppobfdnf2023.30.04.24v.definitiva.pdf    # Report sostenibilità (da aggiungere)
├── README.md                       # Questo file
└── .gitignore                      # File da ignorare (opzionale)
```

##  Report di Sostenibilità

Il report completo `9.gruppobfdnf2023.30.04.24v.definitiva.pdf` e' caricato nella stessa cartella del file HTML per permettere il download dalla pagina web.


##  Caratteristiche Tecniche

### Design e Accessibilità
- **Responsive Design** - Ottimizzato per desktop, tablet e mobile
- **Accessibilità WCAG** - Supporto screen reader, navigazione keyboard, contrasti adeguati
- **Temi Naturali** - Palette colori ispirata alla sostenibilità (verdi, toni naturali)
- **Performance** - Nessuna dipendenza esterna, caricamento rapido

### Tecnologie Utilizzate
- HTML5 semantico
- CSS3 con variabili custom (design system)
- JavaScript vanilla (navigazione smooth scroll, animazioni)
- Font system nativi (nessun font esterno)

### Compatibilità Browser
-  Chrome/Edge 
-  Firefox 
-  Safari 
-  Mobile browsers 

## 🔧 Personalizzazione

### Modificare i Colori
Nel file HTML, sezione `<style>`, modifica le variabili CSS:

```css
:root {
    --color-primary: #2d7a3e;        /* Verde principale */
    --color-primary-light: #4a9d5b;  /* Verde chiaro */
    --color-primary-dark: #1e5a2d;   /* Verde scuro */
    /* ... */
}
```

### Aggiungere Contenuti
Identifica le sezioni nel codice HTML cercando:
- `<section class="container section" id="[nome-sezione]">`
- Aggiungi nuove card duplicando la struttura esistente
- Mantieni la struttura semantica e le classi CSS

### Aggiornare il Report
Sostituisci il file PDF e aggiorna il nome nel link:
```html
<a href="NOME_NUOVO_REPORT.pdf" class="download-button" download>
```

##  Sezioni della Pagina

1. **Header** - Logo, navigazione, menu mobile
2. **Hero** - Introduzione e call-to-action
3. **Piano Strategico** - Overview con statistiche chiave
4. **5 Pilastri** - Card dettagliate per ogni pilastro
5. **Agroecologia** - Pratiche agricole sostenibili
6. **Risultati 2023** - Timeline achievements
7. **Certificazioni** - Grid certificazioni internazionali
8. **Download Report** - Sezione download PDF
9. **Footer** - Link e informazioni aziendali

##  Funzionalità Interactive

- **Smooth Scroll** - Navigazione fluida tra sezioni
- **Menu Mobile** - Responsive navigation per smartphone
- **Active Section Highlight** - Evidenziazione sezione corrente
- **Card Animations** - Fade-in animazioni on scroll
- **Hover Effects** - Feedback visivi su pulsanti e card

##  Troubleshooting

### Il PDF non si scarica
- Verifica che il file PDF sia nella stessa cartella dell'HTML
- Controlla che il nome del file nel codice corrisponda esattamente
- Su GitHub Pages, attendi alcuni minuti dopo il push per la propagazione

### Il sito non appare su GitHub Pages
- Verifica che il repository sia Public
- Controlla che GitHub Pages sia attivato nelle Settings
- Attendi 2-5 minuti per il primo deploy
- Verifica l'URL: `https://[username].github.io/[repo-name]/`

### Stili CSS non applicati
- Controlla che il browser supporti CSS custom properties (variabili)
- Apri la console sviluppatore (F12) per vedere errori
- Prova un hard refresh (Ctrl+F5 o Cmd+Shift+R)

##  Risorse Utili

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)
- [HTML Semantico](https://developer.mozilla.org/en-US/docs/Glossary/Semantics#semantics_in_html)
- [WCAG Accessibilità](https://www.w3.org/WAI/WCAG21/quickref/)

##  Autore
Carmelo Emanuele Sgro'
Progetto sviluppato per Project Work universitario - Analisi Sostenibilità Aziendale

**Azienda Analizzata:** Gruppo BF SpA  
**Settore:** Primario - Agricoltura e Agroindustria  
**Report di Riferimento:** Dichiarazione Non Finanziaria 2023

## 📞 Contatti Gruppo BF

- **Sito Web:** https://www.bfspa.it
- **Investor Relations:** https://www.bfspa.it/investor-relations
- **BF Agricola:** https://www.bfagricola.it
- **CAI:** https://www.consorziagrariditalia.it

## 📝 Licenza

Questo progetto è stato creato per scopi educativi. 

**Nota:** I contenuti relativi al Gruppo BF SpA sono di proprietà dell'azienda. Il report di sostenibilità e i dati presentati sono estratti da documenti pubblici ufficiali.

---

**Data Creazione:** Novembre 2024  
**Ultimo Aggiornamento:** Novembre 2024  
**Versione:** 1.0
