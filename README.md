# NieuweDuinen Roleplay – Website

Officiële website van **NieuweDuinen Roleplay**, een Nederlandse whitelisted FiveM roleplay server.

---

## 📁 Projectstructuur

```
nieuwedijnenrp/
├── index.html               ← Hoofdpagina (Home)
├── css/
│   └── style.css            ← Alle stijlen
├── images/
│   └── logo.png             ← Server logo (transparant)
└── pages/
    ├── nieuws.html          ← Nieuws & aankondigingen
    ├── over-ons.html        ← Over het team
    ├── apv.html             ← Serverregels / APV
    ├── solliciteren.html    ← Whitelist aanvragen
    ├── doneren.html         ← Donatie pakketten
    ├── voorwaarden.html     ← Algemene voorwaarden
    └── privacy.html         ← Privacybeleid
```

---

## 🚀 Lokaal draaien

### Optie 1 – Direct openen (simpelst)
Dubbelklik op `index.html` om de site lokaal in je browser te openen.  
Let op: sommige browsers blokkeren lokale bestanden. Gebruik dan optie 2.

### Optie 2 – Via VS Code Live Server (aanbevolen)
1. Installeer de extensie **Live Server** in VS Code
2. Rechtsklik op `index.html` → **Open with Live Server**
3. De site opent op `http://127.0.0.1:5500`

### Optie 3 – Via Python (geen installatie nodig)
```bash
# Python 3
cd nieuwedijnenrp
python -m http.server 8080
# Open: http://localhost:8080
```

### Optie 4 – Via Node.js
```bash
npx serve .
# Of installeer globaal: npm install -g serve && serve .
```

---

## 🌐 Hosten via GitHub Pages

1. Push de map naar een GitHub repository
2. Ga naar **Settings → Pages**
3. Stel **Source** in op `main` branch, map `/` (root)
4. Je site is live op `https://jouwgebruikersnaam.github.io/repositorynaam`

---

## ✏️ Aanpassen

| Wat aanpassen | Waar |
|---|---|
| Discord link | Zoek op `JOUW_DISCORD_CODE` in alle HTML bestanden en vervang |
| Hero achtergrond | `css/style.css` → `.hero-bg { background: url(...) }` |
| Logo | Vervang `images/logo.png` met jouw logo (zelfde bestandsnaam) |
| Kleuren | `css/style.css` → `:root { --accent: ... }` |
| Staffteam namen | `pages/over-ons.html` → `.staff-grid` sectie |
| Donatie prijzen | `pages/doneren.html` → `.donate-price` elementen |
| Nieuws artikelen | `pages/nieuws.html` → `.news-grid` sectie |

---

## 🎨 Gebruikte technologieën

- **HTML5** – Semantische opmaak
- **CSS3** – Custom properties, Grid, Flexbox, animaties
- **Google Fonts** – Bebas Neue (display) + Outfit (body)
- Geen JavaScript frameworks, geen build tools nodig

---

## 📝 Licentie

© 2026 NieuweDuinen Roleplay. Alle rechten voorbehouden.  
Niet bedoeld voor hergebruik zonder toestemming.
