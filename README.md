# Bonjour, je suis David 👋

Développeur junior passionné d'**automatisation** et de **création de systèmes complets** : serveurs de jeu, bots, pipelines d'IA. J'aime partir d'une idée et l'amener jusqu'à quelque chose qui tourne vraiment, testé et documenté.

Je travaille avec des **assistants IA (Claude)** comme outil de développement. Mon rôle : définir le besoin, concevoir le fonctionnement, intégrer les briques, tester, déboguer et documenter.

---

## 🚀 Mes projets

### 🎞️ [studio-dark](https://github.com/dacunhadavid143-boop/studio-dark) — Montage vidéo automatique calé sur une voix off
Je donne ma voix off et mon texte : le programme repère le moment exact où chaque phrase est dite, cherche des images qui l'illustrent et monte une vidéo verticale calée sur la voix. Une vidéo de 50 s qui me prenait 2 h se fait en ~10 min.
- **Calage voix / texte** : silences détectés + algorithme de programmation dynamique, robuste aux pauses en pleine phrase
- **Deux modèles d'IA** selon la tâche : un rapide pour écrire les plans, un modèle de vision pour trier les images et rejeter logos et watermarks
- **Découpeur de films** : transforme des vidéos entières en banque de scènes nommées automatiquement (1 200+ scènes testées)
- **Clonage de voix local** (XTTS-v2) sur GPU, tests automatiques et scan anti-fuite de clés en CI

`Python` `ffmpeg` `API Claude (texte + vision)` `YouTube Data API` `GitHub Actions`

### 🎮 [EastRP](https://github.com/dacunhadavid143-boop/EastRP) — Serveur de jeu de rôle multijoueur (Arma 3)
Serveur RP complet développé de zéro : identité, économie, téléphone (banque, messagerie), métiers avec chaîne de production et contrôle qualité.
- Architecture **client / serveur** où le serveur fait autorité (anti-triche, appels réseau sur liste blanche)
- **8 modules** indépendants, ~220 fonctions documentées une par une
- Pipeline d'animation : vidéo → capture de mouvement par IA → Blender (Python) → jeu

`SQF` `Python` `PowerShell` `SQL`

### 🎬 [studio-ia](https://github.com/dacunhadavid143-boop/studio-ia) — Création de vidéos par IA générative
Pipeline qui fait travailler **plusieurs IA à la chaîne via leurs API** pour créer une vidéo courte de l'idée au fichier final : script, voix, plans vidéo générés, musique, puis montage automatique avec sous-titres.

`Python` `API d'IA` `ffmpeg` `Automatisation`

### 📈 [binance-dca-bot](https://github.com/dacunhadavid143-boop/binance-dca-bot) — Bot d'investissement automatique
Bot qui réalise un investissement mensuel automatique sur Binance, avec un tableau de bord local pour suivre les achats.

`Python` `API REST`

---

## 🛠️ Compétences

- **Langages :** Python, SQF (Arma 3), PowerShell, notions de SQL
- **Vidéo & audio :** ffmpeg (montage, filtres, détection de plans et de silences), synthèse vocale locale
- **IA :** intégration d'API (texte et vision), prompt engineering, choix de modèle selon coût et tâche
- **Concepts :** architecture client/serveur, API REST, automatisation, persistance des données, sécurité côté serveur
- **Qualité :** tests automatisés (pytest), intégration continue (GitHub Actions), protection des clés API
- **Outils :** Git & GitHub, Blender, serveurs dédiés Windows, assistants IA pour le développement

---

## 📫 Me contacter

- Email : [dacunhadavid143@gmail.com](mailto:dacunhadavid143@gmail.com)

---

<sub>🇬🇧 Junior developer focused on automation: an automated video editor synced to a voice-over, a multiplayer game server (Arma 3), a generative-AI video pipeline and a Binance investment bot. I build with AI assistants and handle design, integration, testing and documentation.</sub>
