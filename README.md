# GXO Procedures - Video Assets & Static Pages

Repository public contenant:
- 📹 **12 vidéos d'instructions multilingues** pour les chauffeurs externes (61 MB)
- 🌐 **Pages HTML statiques** pour le workflow complet chauffeur

## 📹 Vidéos disponibles

Toutes les vidéos sont accessibles via GitHub CDN:

```
https://raw.githubusercontent.com/ayoubdil1972-stack/gxo-video-assets/main/videos/instructions-{langue}.mp4
```

### Langues supportées (12)

- 🇳🇱 **Néerlandais** (nl) - instructions-nl.mp4
- 🇫🇷 **Français** (fr) - instructions-fr.mp4
- 🇩🇪 **Allemand** (de) - instructions-de.mp4
- 🇫🇮 **Finnois** (fi) - instructions-fi.mp4
- 🇩🇰 **Danois** (da) - instructions-da.mp4
- 🇨🇿 **Tchèque** (cs) - instructions-cs.mp4
- 🇧🇬 **Bulgare** (bg) - instructions-bg.mp4
- 🇵🇱 **Polonais** (pl) - instructions-pl.mp4
- 🇷🇴 **Roumain** (ro) - instructions-ro.mp4
- 🇮🇹 **Italien** (it) - instructions-it.mp4
- 🇵🇹 **Portugais** (pt) - instructions-pt.mp4
- 🇭🇷 **Croate** (hr) - instructions-hr.mp4

## 🌐 Pages HTML Statiques

Workflow complet pour chauffeurs externes accessible via GitHub Pages:

### URLs GitHub Pages

**Base URL**: `https://ayoubdil1972-stack.github.io/gxo-video-assets/pages/`

| Page | URL | Description |
|------|-----|-------------|
| **QR Code** | `/qrcode-chauffeur.html` | Point d'entrée avec scan QR code |
| **Langue** | `/chauffeur-langue.html` | Sélection parmi 12 langues |
| **Vidéo** | `/chauffeur-video.html?lang=XX` | Vidéo d'instructions (XX = code langue) |
| **Inscription** | `/chauffeur-inscription.html` | Formulaire chauffeur |
| **Tâches** | `/chauffeur-taches.html?id=XXX` | 5 tâches de sécurité |
| **Dashboard** | `/accueil-chauffeur.html` | Récapitulatif et félicitations |

### Exemples d'URLs complètes

```
# Page QR Code
https://ayoubdil1972-stack.github.io/gxo-video-assets/pages/qrcode-chauffeur.html

# Vidéo néerlandaise
https://ayoubdil1972-stack.github.io/gxo-video-assets/pages/chauffeur-video.html?lang=nl

# Vidéo italienne
https://ayoubdil1972-stack.github.io/gxo-video-assets/pages/chauffeur-video.html?lang=it

# Tâches chauffeur
https://ayoubdil1972-stack.github.io/gxo-video-assets/pages/chauffeur-taches.html?id=12
```

## 🚀 Workflow Complet

```
1. QR Code
   └─> 2. Sélection Langue (12 options)
         └─> 3. Vidéo Instructions (lecture obligatoire)
               └─> 4. Inscription (pseudo, entreprise, quai)
                     └─> 5. Tâches de Sécurité (5 validations)
                           └─> 6. Dashboard Chauffeur (félicitations)
```

## 📱 Compatibilité

- ✅ Desktop (Chrome, Firefox, Safari, Edge)
- ✅ Mobile (iOS Safari, Chrome Android)
- ✅ Tablette (iPad, Android)
- ✅ Support Range Requests (streaming vidéo iOS)
- ✅ 100% Responsive Design

## 🎨 Technologies

- **Frontend**: HTML5, TailwindCSS CDN, Font Awesome
- **Vidéos**: MP4, hébergées sur GitHub CDN
- **Hébergement**: GitHub Pages (gratuit)
- **Stockage**: sessionStorage pour persistance workflow

## 📊 Statistiques

| Métrique | Valeur |
|----------|--------|
| Vidéos | 12 langues |
| Taille totale vidéos | 61 MB |
| Pages HTML | 6 pages |
| Hébergement | GitHub (gratuit) |
| Compatible mobile | ✅ Oui |
| Range Requests | ✅ Oui |

## 🔧 Utilisation

### Pour intégrer dans votre application

```javascript
// Charger une vidéo
const videoUrl = 'https://raw.githubusercontent.com/ayoubdil1972-stack/gxo-video-assets/main/videos/instructions-nl.mp4';

// Lien vers workflow complet
const workflowUrl = 'https://ayoubdil1972-stack.github.io/gxo-video-assets/pages/qrcode-chauffeur.html';
```

### QR Code

Générez un QR code pointant vers:
```
https://ayoubdil1972-stack.github.io/gxo-video-assets/pages/qrcode-chauffeur.html
```

## 📦 Structure du Repository

```
gxo-video-assets/
├── videos/                          # 12 vidéos MP4 (61 MB)
│   ├── instructions-nl.mp4
│   ├── instructions-fr.mp4
│   └── ...
├── pages/                           # Pages HTML statiques
│   ├── static/                      # Assets (logos, images)
│   │   ├── gxo-logo-official.svg
│   │   └── warehouse-bg-hd.jpg
│   ├── qrcode-chauffeur.html       # Page QR code
│   ├── chauffeur-langue.html       # Sélection langue
│   ├── chauffeur-video.html        # Lecteur vidéo
│   ├── chauffeur-inscription.html  # Formulaire
│   ├── chauffeur-taches.html       # Tâches sécurité
│   └── accueil-chauffeur.html      # Dashboard
├── index.html                       # Redirection vers workflow
└── README.md                        # Ce fichier
```

## 🔗 Liens Utiles

- **Repository**: https://github.com/ayoubdil1972-stack/gxo-video-assets
- **GitHub Pages**: https://ayoubdil1972-stack.github.io/gxo-video-assets/
- **Site Principal** (privé): https://github.com/ayoubdil1972-stack/gxo-procedures-moissy
- **Production**: https://gxo-procedures-moissy.pages.dev/

## 📞 Support

Pour toute question:
- Repository: https://github.com/ayoubdil1972-stack/gxo-video-assets/issues
- Site GXO: https://gxo-procedures-moissy.pages.dev/

---

**Créé pour**: GXO Logistics - Site de Moissy-Cramayel  
**Date**: Février 2026  
**Version**: 1.0.0
