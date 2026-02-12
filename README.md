# GXO Procedures - Video Assets

Repository public contenant les **12 vidéos d'instructions multilingues** pour les chauffeurs externes.

## 📹 Vidéos disponibles

Toutes les vidéos sont accessibles via GitHub CDN:

```
https://raw.githubusercontent.com/ayoubdil1972-stack/gxo-video-assets/main/videos/instructions-{langue}.mp4
```

### Langues supportées (12)

| Langue | Code | Fichier |
|--------|------|---------|
| 🇳🇱 Néerlandais | `nl` | instructions-nl.mp4 (5.0 MB) |
| 🇫🇷 Français | `fr` | instructions-fr.mp4 (5.2 MB) |
| 🇩🇪 Allemand | `de` | instructions-de.mp4 (5.0 MB) |
| 🇫🇮 Finnois | `fi` | instructions-fi.mp4 (5.0 MB) |
| 🇩🇰 Danois | `da` | instructions-da.mp4 (4.5 MB) |
| 🇨🇿 Tchèque | `cs` | instructions-cs.mp4 (5.0 MB) |
| 🇧🇬 Bulgare | `bg` | instructions-bg.mp4 (5.2 MB) |
| 🇵🇱 Polonais | `pl` | instructions-pl.mp4 (5.1 MB) |
| 🇷🇴 Roumain | `ro` | instructions-ro.mp4 (5.2 MB) |
| 🇮🇹 Italien | `it` | instructions-it.mp4 (5.1 MB) |
| 🇵🇹 Portugais | `pt` | instructions-pt.mp4 (5.2 MB) |
| 🇭🇷 Croate | `hr` | instructions-hr.mp4 (5.2 MB) |

**Taille totale**: 61 MB

## 🌐 Site Web Principal

Le site web avec l'interface utilisateur complète est hébergé sur:

**https://gxo-procedures-moissy.pages.dev/**

### URLs principales du workflow chauffeur:

- **QR Code**: https://gxo-procedures-moissy.pages.dev/qrcode-chauffeur
- **Sélection langue**: https://gxo-procedures-moissy.pages.dev/chauffeur/langue
- **Vidéo instructions**: https://gxo-procedures-moissy.pages.dev/chauffeur/video?lang={langue}
- **Inscription**: https://gxo-procedures-moissy.pages.dev/chauffeur/inscription
- **Tâches**: https://gxo-procedures-moissy.pages.dev/chauffeur/taches?id={id}
- **Dashboard**: https://gxo-procedures-moissy.pages.dev/accueil-chauffeur

## 🔧 Utilisation

### Pour intégrer les vidéos dans votre application

```javascript
// Exemple: charger la vidéo néerlandaise
const videoUrl = 'https://raw.githubusercontent.com/ayoubdil1972-stack/gxo-video-assets/main/videos/instructions-nl.mp4';

// Exemple: charger la vidéo italienne
const videoUrl = 'https://raw.githubusercontent.com/ayoubdil1972-stack/gxo-video-assets/main/videos/instructions-it.mp4';
```

### Caractéristiques techniques

- **Format**: MP4 (H.264)
- **Résolution**: Optimisée pour mobile et desktop
- **Streaming**: Support Range Requests (compatible iOS Safari)
- **CDN**: GitHub CDN avec cache mondial
- **CORS**: Enabled avec `crossorigin="anonymous"`

## 📊 Statistiques

| Métrique | Valeur |
|----------|--------|
| Nombre de vidéos | 12 |
| Taille totale | 61 MB |
| Hébergement | GitHub CDN (gratuit) |
| Compatible mobile | ✅ Oui |
| Range Requests | ✅ Oui |

## 🔗 Liens

- **Repository**: https://github.com/ayoubdil1972-stack/gxo-video-assets
- **Site Principal**: https://gxo-procedures-moissy.pages.dev/
- **Repository Site Principal**: https://github.com/ayoubdil1972-stack/gxo-procedures-moissy

---

**Créé pour**: GXO Logistics - Site de Moissy-Cramayel  
**Date**: Février 2026  
**Version**: 1.0.0
