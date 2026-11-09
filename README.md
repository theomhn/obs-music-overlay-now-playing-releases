# Music Overlay Now Playing - Releases Officielles

[![OBS Studio](https://img.shields.io/badge/OBS%20Studio-31%2B-%23302E31.svg?style=for-the-badge&logo=obsstudio&logoColor=white)](https://obsproject.com/)
[![Windows](https://img.shields.io/badge/Windows-0078D6.svg?style=for-the-badge&logo=windows&logoColor=white)](https://www.microsoft.com/windows)
[![Release](https://img.shields.io/github/v/release/theomhn/obs-music-overlay-now-playing-releases?style=for-the-badge&logo=github&color=brightgreen)](https://github.com/theomhn/obs-music-overlay-now-playing-releases/releases/latest)
[![License](https://img.shields.io/badge/License-GPLv2-green.svg?style=for-the-badge)](https://github.com/theomhn/obs-music-overlay-now-playing-releases/releases)
[![Author](https://img.shields.io/badge/Author-theomhn-blue.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/theomhn)
[![Website](https://img.shields.io/badge/Website-theomenchon.fr-black.svg?style=for-the-badge)](https://theomenchon.fr)

Bienvenue sur le **dépôt officiel de distribution des releases** du plugin **Music Overlay Now Playing** (`obs-music-overlay-now-playing`) pour **OBS Studio** (Windows 10 / 11 64-bit).

Ce plugin natif C++20 affiche en temps réel sur vos scènes et overlays de stream le morceau de musique en cours de lecture avec une fluidité exceptionnelle, sans clé d'API ni configuration complexe.

Grâce à l'intégration directe avec les **Windows System Media Transport Controls (SMTC)**, il détecte automatiquement tous vos lecteurs multimédias : **Spotify**, **Apple Music**, **Deezer**, **Tidal**, **Amazon Music**, **YouTube Music / Chrome / Edge**, **VLC**, etc.

---

## Sommaire

- [✨ Fonctionnalités](#-fonctionnalités)
- [⚙️ Aperçu des options](#️-aperçu-des-options)
- [📥 Téléchargement & Installation](#-téléchargement--installation)
  - [Méthode 1 : Assistant automatique install.bat (Recommandé)](#-méthode-1--assistant-automatique-installbat-recommandé)
  - [Méthode 2 : Installation manuelle](#️-méthode-2--installation-manuelle)
- [🚀 Utilisation dans OBS Studio](#-utilisation-dans-obs-studio)
- [👤 Auteur & Copyright](#-auteur--copyright)
- [📄 Licence](#-licence)

---

## ✨ Fonctionnalités

- 🎵 **Détection universelle (Windows SMTC)** : Détection temps réel et automatique des médias en cours de lecture (avec priorité intelligente accordée à Spotify).
- 🖼️ **Pochette d'album haute fidélité** : Extraction dynamique des pochettes en mémoire avec coins arrondis personnalisables.
- 🎨 **Styles graphiques & Effets intégrés** :
  - **Standard / Clean**
  - **Effet VHS vintage**
  - **Pellicule 8mm**
  - **Duotone**
  - **Noir & Blanc argentique**
  - **Glitch futuriste**
- 🎛️ **Simulateur Spectrum / VU-mètre** : Visualisation audio dynamique en barres verticales ou horizontales avec vitesse, réactivité et dynamisme réglables.
- ⏱️ **Barre de progression & Synchronisation temps réel** : Timeline réactive (détection instantanée des sauts de lecture, pauses et remises à zéro du morceau).
- ✏️ **Typographie ultra-personnalisable** :
  - Sélecteurs natifs de polices OBS pour le Titre, l'Artiste et l'Album.
  - Couleurs, tailles, contours (*outline / stroke*), interlignage et styles indépendants.
  - Transformation de la casse du texte (*None, UPPERCASE, lowercase, Title Case, CamelCase*).
  - Défilement textuel dynamique fluide (*smooth scrolling*) pour les titres longs.
  - Option d'affichage de l'artiste et du titre sur une ligne unique ou lignes séparées.
- 📐 **Mises en page flexibles** : Disposition horizontale classique ou verticale (idéale pour les lives TikTok, YouTube Shorts et Instagram Reels).
- 🎬 **Arrière-plans animés & Vidéos** : Support des images statiques (PNG/JPG), des GIFs animés multi-images et des vidéos en boucle (MP4, QuickTime MOV/QT, AVI, WebM).
- 👻 **Gestion intelligente de l'affichage (Auto-Hide)** :
  - Masquage automatique à la pause ou à l'arrêt du lecteur.
  - Affichage temporaire (ex: 10 secondes) uniquement lors d'un changement de piste.
- 🔄 **Mise à jour intégrée** : Détection asynchrone des nouvelles versions directement dans les propriétés de la source OBS.
- 🌍 **Internationalisation complète (14 langues)** : Français, Anglais, Allemand, Espagnol, Italien, Portugais, Polonais, Russe, Ukrainien, Turc, Japonais, Coréen, Chinois Simplifié et Chinois Traditionnel.

---

## ⚙️ Aperçu des options

| Catégorie | Paramètres disponibles |
|-----------|------------------------|
| **Carte & Apparence** | Dimensions (largeur / hauteur), couleur et opacité du fond, rayon des coins, styles visuels (VHS, 8mm, Glitch, etc.), orientation verticale |
| **Arrière-plan personnalisé** | Image, GIF animé ou vidéo en boucle (MP4, MOV, WebM), opacité réglable |
| **Pochette d'album** | Afficher / masquer, rayon des coins arrondis |
| **Titre, Artiste, Album** | Police de caractères native, taille, couleur, activation du contour, épaisseur et couleur, casse du texte, interlignage, album sur sa propre ligne |
| **Barre de progression** | Afficher / masquer la timeline et la durée, couleur de remplissage, couleur de fond, hauteur, espacement |
| **Spectrum / VU-mètre** | Activer / désactiver, orientation (horizontale/verticale), couleur, nombre de barres, réactivité (ms), dynamisme (%) |
| **Animation & Défilement** | Vitesse de défilement du texte, animation de transition lors du changement de piste |
| **Masquage auto** | Masquer à la pause, affichage déclenché uniquement au changement de morceau avec durée configurable |
| **Mises à jour** | Statut de la version installée, vérification en un clic et bouton de téléchargement direct |

---

## 📥 Téléchargement & Installation

Rendez-vous dans la section [**Releases**](https://github.com/theomhn/obs-music-overlay-now-playing-releases/releases/latest) et téléchargez l'archive correspondant à votre installation d'OBS Studio :

* **OBS Studio 33 et ultérieur** : `obs-music-overlay-now-playing-<version>_modern.zip`
* **OBS Studio 32 et antérieur** : `obs-music-overlay-now-playing-<version>_legacy.zip`
* **OBS Studio Portable** : `obs-music-overlay-now-playing-<version>_portable.zip`

---

### 🚀 Méthode 1 : Assistant automatique `install.bat` (Recommandé)

Chaque archive contient l'assistant d'installation Windows automatisé :

1. Dézippez l'archive téléchargée.
2. Double-cliquez sur **`install.bat`**.
3. L'assistant détecte automatiquement votre version d'OBS Studio et ferme proprement l'application si elle est ouverte.
4. Appuyez simplement sur **`[Entrée]`** pour installer ou mettre à jour le plugin !
5. Relancez OBS Studio.

---

### 🛠️ Méthode 2 : Installation manuelle

1. Fermez complètement OBS Studio.
2. Décompressez l'archive téléchargée :
   * **OBS Studio 33+ (Modern)** : Décompressez le dossier `obs-music-overlay-now-playing` dans :  
     `%ProgramData%\obs-studio\plugins\` *(ou `%APPDATA%\obs-studio\plugins\`)*
   * **OBS Studio 32- (Legacy)** : Décompressez le dossier `obs-music-overlay-now-playing` (contenant le sous-dossier `bin/64bit`) dans :  
     `%ProgramData%\obs-studio\plugins\`
   * **OBS Studio Portable** : Extrayez et fusionnez les dossiers `obs-plugins/` et `data/` à la racine de votre installation OBS Portable.
3. Relancez OBS Studio.

---

## 🚀 Utilisation dans OBS Studio

1. Démarrez la lecture d'un morceau sur votre application musicale (Spotify, Deezer, Apple Music, YouTube Music, etc.).
2. Dans OBS Studio, rendez-vous dans le panneau **Sources**.
3. Cliquez sur **`+`** (Ajouter une source) et sélectionnez **`Music Overlay Now Playing`**.
4. Donnez un nom à votre source (ex: *Overlay Musique*) et validez.
5. Ajustez l'apparence, les polices, les couleurs et les dimensions dans la fenêtre des propriétés pour correspondre parfaitement à votre identité visuelle !

---

## 👤 Auteur & Copyright

Développé avec passion par **Théo Menchon (theomhn)** :
- 🌐 **Site web** : [theomenchon.fr](https://theomenchon.fr)
- 🐙 **GitHub** : [@theomhn](https://github.com/theomhn)
- ✉️ **Contact** : [contact@theomenchon.fr](mailto:contact@theomenchon.fr)

---

## 📄 Licence

Ce projet est distribué sous licence libre **GNU General Public License v2.0 (GPLv2)**.  
Consultez le fichier `LICENSE` pour plus de détails.
