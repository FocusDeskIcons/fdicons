# FD Icons

**FD Icons** est une librairie d’icônes sous forme de **web font**, générée avec IcoMoon et prête à être utilisée dans tous vos projets web (HTML, CSS, JS).

✔️ Léger  
✔️ Facile à intégrer  
✔️ Compatible CDN (jsDelivr)  
✔️ Classes CSS simples (`fdi fdi-icon-name`)

---

## 📦 Contenu du package
fdicons/
├─ dist/
│  ├─ fonts/
│  │  ├─ fdicons.otf
│  │  ├─ fdicons.ttf
│  │  ├─ fdicons.woff
│  │  └─ fdicons.woff2
│  │
│  └─ css/
│     ├─ fdi.css
│     └─ fdi.min.css
│
├─ demo/
│  └─ demo.html
│
├─ data/
│  └─ fdicons.json
│
├─ LICENSE
├─ README.md
└─ package.json

Créé moi maintenant un package.json
---

## 🚀 Installation (via CDN)

La manière la plus simple d’utiliser **FD Icons** est via **jsDelivr**.

### Ajouter le CSS

```html
<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/FocusDeskIcons/fdicons@v1.0.0/dist/css/fdi.min.css"
/>


---

🧩 Utilisation

Les icônes s’utilisent avec la balise <i> et les classes CSS.

<i class="fdi fdi-arrow-right"></i>
<i class="fdi fdi-home"></i>
<i class="fdi fdi-user"></i>

Règles importantes

La classe fdi est obligatoire

Le nom de l’icône commence toujours par fdi-



---

🎨 Personnalisation

Les icônes sont des fonts, tu peux donc les styliser facilement avec du CSS :

.fdi {
  font-size: 24px;
  color: #2563eb;
}

.icon-large {
  font-size: 48px;
}

<i class="fdi fdi-heart icon-large"></i>


---

📊 Données des icônes (JSON)

Le fichier fdicons.json contient la liste complète des icônes avec :

nom

classe CSS

valeur content


📍 Chemin :

data/fdicons.json

📥 Accès via CDN :

https://cdn.jsdelivr.net/gh/FocusDeskIcons/fdicons/data/fdicons.json

Exemple de structure

{
  "font": "fdicons",
  "prefix": "fdi",
  "count": 1200,
  "icons": [
    {
      "name": "arrow-right",
      "class": "fdi-arrow-right",
      "content": "\\f3ad"
    }
  ]
}

👉 Idéal pour créer un site de preview, une recherche d’icônes, ou un copier-coller automatique.


---

🧪 Démo locale

Ouvre le fichier :

demo/demo.html

Ou intègre directement le CDN dans ton projet.


---

🏷 Versioning

Les versions sont gérées via des tags GitHub.

Exemple :

v1.0.0

Utilisation CDN versionnée :

<link
  rel="stylesheet"
  href="https://cdn.jsdelivr.net/gh/FocusDeskIcons/fdicons@1.0.0/dist/css/fdi.min.css"
/>


---

📝 Licence

Ce projet est sous licence MIT.
Libre d’utilisation pour projets personnels et commerciaux.


---

🤝 Contribution

Les contributions sont les bienvenues :

ajout d’icônes

corrections

améliorations de la documentation


➡️ Ouvre une issue ou une pull request.


---

⭐ Support

Si ce projet t’aide :

⭐ mets une étoile sur GitHub

partage-le avec la communauté



---

© FocusDeskIcons

---
