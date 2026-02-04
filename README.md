# Stresa Immobiliare SRL - Sito Web Ufficiale

> Sito statico elegante per agenzia immobiliare di prestigio sul Lago Maggiore

## 🏠 Overview

Sito web professionale per **Stresa Immobiliare SRL**, agenzia immobiliare specializzata in proprietà di lusso nella zona del Lago Maggiore. Design moderno con palette colori corporate (blu navy, grigio elegante, accenti dorati/beige).

## 🎨 Design

**Ispirazione design:**
- [Stresa Luxury Real Estate](https://www.stresa.biz/) - Agenzia leader sul Lago Maggiore
- [SIS Real Estate](https://www.sis-realestate.it/en/) - Design elegante e professionale
- [Alpino Immobiliare](https://www.alpinoimmobiliare.it/en/) - Layout pulito e moderno

**Palette colori:**
- Navy (#1a2540) - Colore principale corporate
- Gold (#c9a96e) - Accenti luxury
- Beige (#f5f2ed) - Background sezioni alternate
- Gray (#5a6072) - Testi secondari

**Typography:**
- Headings: Playfair Display (serif elegante)
- Body: Inter (sans-serif moderna)

## 📦 Stack Tecnologico

- HTML5 semantico
- CSS3 moderno (Grid, Flexbox, Custom Properties)
- Google Fonts (Playfair Display + Inter)
- Unsplash per immagini hero e gallery
- GitHub Pages per hosting

## 🚀 Deployment

Sito deployato su GitHub Pages:
- **Repository:** [giobi/stresaimmobiliare](https://github.com/giobi/stresaimmobiliare)
- **URL:** https://giobi.github.io/stresaimmobiliare

## 📄 Struttura

```
├── index.html          # Pagina principale (landing page)
├── style.css          # Stylesheet completo
└── README.md          # Documentazione
```

## 📝 Sezioni

1. **Hero** - Hero section con foto panoramica Lago Maggiore + CTA
2. **Chi Siamo** - Info agenzia con statistiche (35+ anni esperienza)
3. **Servizi** - 4 servizi principali (compravendita, gestione, consulenza, network)
4. **Gallery** - 3 foto rappresentative (ville, lago, interni luxury)
5. **Contatti** - Info contatto + form (placeholder, non ancora attivo)
6. **Footer** - Link utili e info corporate

## 🔧 Personalizzazione

### Aggiornare i dati aziendali

Nel file `index.html`, cercare e sostituire i placeholder:

```html
<!-- Indirizzo -->
<p>Corso Italia, 123<br>28838 Stresa (VB)</p>

<!-- Telefono -->
<p>+39 0323 XXX XXX</p>

<!-- Email -->
<p>info@stresaimmobiliare.com</p>

<!-- P.IVA -->
<p>P.IVA: XXXXXXXXXXX</p>
```

### Attivare il form contatti

Per attivare il form contatti, integrare con un servizio backend (Formspree, Netlify Forms, o custom PHP/Node.js handler):

1. Rimuovere `disabled` dal bottone submit
2. Configurare `action` e `method` del form
3. Aggiungere gestione POST lato server

### Cambiare immagini

Sostituire gli URL Unsplash con immagini proprietarie:

```css
/* Hero background - style.css line ~180 */
background: url('path/to/your/hero-image.jpg') center/cover;
```

```html
<!-- Gallery e about images - index.html -->
<img src="path/to/your/image.jpg" alt="Descrizione">
```

## 📱 Responsive Design

Sito completamente responsive con breakpoint:
- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: 320px - 767px

## 🌐 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Opera 76+

## 📄 License

© 2026 Stresa Immobiliare SRL. Tutti i diritti riservati.

## 📞 Supporto

Per modifiche al sito web, contattare: info@stresaimmobiliare.com

---

**Sviluppato con ❤️ per Stresa Immobiliare SRL**
