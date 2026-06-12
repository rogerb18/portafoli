# Portafoli · Roger Buendia Salazar

Portafoli personal estàtic, multillenguatge (català, castellà i anglès), responsive i amb mode clar/fosc.

## Estructura

```
.
├── index.html
├── css/styles.css
├── js/main.js
└── netlify.toml
```

## Característiques

- Tres idiomes amb canvi instantani (CA / ES / EN), amb preferència desada al navegador.
- Mode clar i fosc.
- Seccions: sobre mi, experiència, estudis, habilitats, projectes i contacte.
- Els projectes es carreguen automàticament des de l'API pública de GitHub (`rogerb18`).
- Disseny responsive amb menú per a mòbil.

## Veure en local

Obre `index.html` al navegador, o serveix la carpeta amb qualsevol servidor estàtic:

```
npx serve .
```

## Desplegament a Netlify

1. Entra a [app.netlify.com](https://app.netlify.com) → **Add new site** → **Deploy manually**.
2. Arrossega la carpeta del projecte a la zona d'arxius. Llest.

Alternativament, connecta un repositori de Git i Netlify desplegarà automàticament a cada `push` (publish directory: `.`).
