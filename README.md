# 🕋 Guide Omra & Hajj — Web App

Application web progressive (PWA) pour les pèlerins marocains. Utilisable sur iPhone en l'ajoutant à l'écran d'accueil.

## Fonctionnalités

- 🤲 **Fiches Duas** — 23 étapes avec texte arabe, phonétique et traduction française
- 🌙 **Guide Omra** — 10 sections du départ à la fin des rites
- 🕋 **Guide Hajj** — Du 8 Dhul-Hijja au Tawaf Al-Wadâ'
- 🔊 **Lecture vocale** — Écoute les textes en français (TTS)
- 📱 **Swipe** — Navigation fluide par glissement entre les sections
- 📶 **Hors-ligne** — Fonctionne sans internet après la première visite

## Installation sur iPhone

1. Ouvrir le lien dans **Safari** (obligatoire, pas Chrome)
2. Appuyer sur l'icône **Partager** (carré avec flèche vers le haut)
3. Sélectionner **"Sur l'écran d'accueil"**
4. Confirmer → L'app apparaît comme une vraie application

## Déploiement sur GitHub Pages

1. Créer un repository public sur GitHub
2. Uploader tous les fichiers du dossier
3. Aller dans **Settings → Pages → Source → main branch**
4. L'app sera disponible à `https://[username].github.io/[repo-name]/`

## Structure des fichiers

```
├── index.html          # App principale
├── duas.js             # Données de toutes les duas
├── guide-omra.js       # Contenu du guide Omra
├── guide-hajj.js       # Contenu du guide Hajj
├── manifest.json       # Configuration PWA
├── sw.js               # Service Worker (hors-ligne)
├── icons/
│   ├── icon-192.png    # Icône app (à créer)
│   └── icon-512.png    # Icône app (à créer)
└── README.md
```

## Icônes

Pour les icônes, créer deux images PNG avec la Kaaba ou le croissant :
- `icons/icon-192.png` — 192×192 pixels
- `icons/icon-512.png` — 512×512 pixels

Vous pouvez utiliser [Favicon.io](https://favicon.io) ou n'importe quel éditeur d'image.

## Sources

- Sahih Al-Bukhari, Sahih Muslim, At-Tirmidhi, Ibn Mâjah
- Ibn Qudâma (Al-Mughnî), Al-Nawawi (Al-Majmû')
- Ministère des Habous du Maroc
- Conseil Européen pour la Fatwa et la Recherche (CEFR)

---
*Taqabbalallâhu minnâ wa minkum — Qu'Allah accepte de nous et de vous 🤲*
