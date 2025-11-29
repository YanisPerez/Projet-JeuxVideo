# Projet de Jeu Vidéo Écologique

---

<details>
  <summary><h2>👨‍💻 1. Répartition des rôles</h2></summary>

**Répartition des rôles**
- Game Designer (GD)
- Dev 1 (Gameplay)
- Dev 2 (Tech/UI)
- Artiste
- Sound Designer
</details>

---

<details>
  <summary><h2>📆 1. PLANNING PAR RÔLE ET TÂCHES COMMUNES</h2></summary>
  
| Rôle | Tâches | Outils / Applications |
|------|--------|--------------------|
| **Game Designer (GD)** | - Document du concept<br>- Cahier des charges + boucle de gameplay<br>- Croquis des niveaux (maquettes UI sur Figma)<br>- Level design des 2 premiers niveaux<br>- Création des niveaux + scripts d’événements<br>- Ajustement du gameplay<br>- Tests internes (collecter les retours)<br>- Tests utilisateurs + corrections<br>- Dossier de présentation du projet | Notion, Google Docs, Figma, Unity Tilemap (2D), Google Sheets (équilibrage), Unity Timeline, Google Forms, Excel, Canva, Google Slides |
| **Dev 1 (Gameplay Programmer)** | - Prototype minimal (déplacements, interactions)<br>- Programmation des mécaniques de base<br>- Collisions, inventaire, interactions<br>- IA basique<br>- Feedbacks (retours visuels/sons liés au gameplay)<br>- Fonctionnalités secondaires<br>- Correction des bugs majeurs<br>- Optimisation du gameplay<br>- Ajustement de la difficulté | Unity, C#, Visual Studio Code, Unity Collisions 2D/3D, Unity NavMesh (IA si 3D), Unity Profiler, Deep Profiling |
| **Dev 2 (Tech / UI Programmer)** | - Mise en place du projet (Unity/Godot)<br>- Gestion des inputs + caméras<br>- UI de base (menus, HUD)<br>- Système de sauvegarde (JSON, PlayerPrefs)<br>- Intégration des assets artistiques<br>- Polish UI<br>- Fonctionnalités secondaires tech<br>- Correction de bugs<br>- Optimisation technique<br>- Build final + compatibilité plateformes | Unity, Unity Input System, Unity UI Toolkit / Canvas, Figma (UI mockups fournis par GD), JSON / PlayerPrefs, Unity Profiler, Unity Build Tools, itch.io / Steamworks |
| **Artiste (2D/3D)** | - Tests de style graphique<br>- Concept arts<br>- Premiers assets simples<br>- Création des assets principaux<br>- Animations simples<br>- Nouveaux environnements<br>- Effets visuels simples<br>- UI définitive (style visuel + icons)<br>- Polissage graphique<br>- Optimisation textures<br>- Petits effets visuels<br>- Trailer du jeu<br>- Screenshots officiels | Aseprite (2D), Photoshop, Blender (3D, animations), Unity Particle System, TexturePacker, Unity VFX, Premiere Pro, OBS Studio |
| **Sound Designer** | - Recherches sonores + ambiance générale<br>- Bruitages de base (pas, objets, interface)<br>- Musique d’ambiance 1 & 2<br>- Musiques finales<br>- Bruitages restants<br>- Mastering audio<br>- Mix final pour le trailer | YouTube Audio Library, Audacity, Reaper, freesound.org, FL Studio|

| Tâche / Domaine                           | Rôles impliqués                    | Type de collaboration |
|-------------------------------------------|------------------------------------|------------------------|
| Document du concept                       | GD, Artiste                        | Le GD définit, l’artiste illustre |
| Cahier des charges + gameplay loop        | GD, Dev 1, Dev 2                   | Le GD décrit, les Devs valident faisabilité |
| Croquis & style graphique                 | GD, Artiste                        | Alignement direction artistique |
| Prototype minimal                         | GD, Dev 1                          | GD définit, Dev 1 implémente |
| Mise en place du projet Unity             | Dev 1, Dev 2                       | Partage de structure & conventions |
| Intégration premiers assets               | Dev 1, Artiste                     | Artiste produit, Dev intègre |
| Recherches ambiance sonore                | Sound, GD                          | Co-définition de l’ambiance |
| Mécaniques de base (collisions, inventaire) | GD, Dev 1                        | Le GD décrit, Dev 1 code |
| UI de base (menus, HUD)                   | Dev 2, Artiste, GD                 | Artiste design, Dev implémente, GD valide |
| Système de sauvegarde                     | Dev 2, GD                          | Ajustements selon besoins gameplay |
| Level design premiers niveaux             | GD, Artiste, Dev 1/2               | GD design, artiste crée assets, Dev place |
| Bruitages de base                         | Sound, Devs                        | Sound crée, Devs intègrent |
| IA basique                                | GD, Dev 1                          | GD définit comportements, Dev code |
| Intégration assets + polish UI            | Dev 2, Artiste                     | Ajustements continus des visuels |
| Création des niveaux                      | GD, Dev 1/2, Artiste               | Production conjointe gameplay + visuels |
| Scripts d’événements                      | GD, Dev 1                          | GD décrit, Dev code |
| Nouveaux environnements                   | Artiste, GD, Devs                  | Cohérence entre level design et assets |
| Effets visuels                            | Artiste, Dev 2                     | Artiste produit, Dev intègre |
| Musiques d’ambiance                       | Sound, GD                          | Direction musicale fixée par GD |
| Fonctionnalités secondaires + debug       | Devs, GD                           | Ajustements selon tests |
| UI définitive                             | Artiste, Dev 2, GD                 | Design + implémentation + validation |
| Ajustement du gameplay                    | GD, Devs                           | Boucles de tests internes |
| Musiques finales + bruitages restants     | Sound, GD, Devs                    | Ajustements selon niveaux |
| Optimisation (perf, textures, VFX)        | Devs, Artiste                      | Travail commun sur performance & visuels |
| Mastering audio                           | Sound, GD                          | Validation selon intention du jeu |
| Tests utilisateurs + corrections          | GD, Devs, Artiste, Sound           | Tous concernés par retours |
| Build final + compatibilité plateformes   | Devs, GD                           | Tests, validation, réglages |
| Trailer du jeu                            | Artiste, Sound, GD                 | Vidéo + audio + narration |
| Dossier de présentation                   | GD, Artiste                        | Contenu + visuels |


</details>

---

<details>
  <summary><h2>📆 3. PLANNING MOIS PAR MOIS</h2></summary>
  
### Mois 1 — Pré-production (Bases + Prototype)

**- GD**
- Document du concept
- Cahier des charges + boucle de gameplay
- Croquis des niveaux
Outils : Notion, Google Docs, Figma (croquis UI)

**- Dev 1**
- Prototype minimal (déplacements, interactions)
Outils :
Unity, Visual Studio Code

**- Dev 2**
- Mise en place du projet (Unity)
- Gestion des inputs + caméras
Outils :
Unity Input System

**- Artiste**
- Tests de style graphique
- Concept arts + premiers assets simples
Outils :
Aseprite (2D), Photoshop, Blender (3D)

**- Sound**
- Recherches sonores + ambiance générale
Outils :
YouTube audio library, Audacity, Reaper
Livrable : mini prototype jouable 2–3 minutes.

### Mois 2 — Développement du cœur du jeu
**- Dev 1**
- Programmation mécaniques de base
- Collisions, inventaire simple, interactions
Outils :
Unity (collisions 2D/3D), C#, Rider/VSCode

**- Dev 2**
- UI de base (menus, HUD)
- Système de sauvegarde
Outils :
Figma (UI mockups), Unity UI Toolkit, PlayerPrefs

**- Artiste**
- Assets principaux
- Animations simples
Outils :
Blender (animations), Aseprite (sprites), Photoshop

**- GD**
- Level design des 2 premiers niveaux
Outils :
Unity Tilemap (2D), ProBuilder (3D)

**- Sound**
- Bruitages de base (pas, objets, interface)
Ouils :
Audacity, freesound.org, Reaper

### Mois 3 — Contenu jouable
**- Dev 1**
- IA basique
- Feedbacks
Outils :
Unity NavMesh (si 3D), scripts C#

**- Dev 2**
- Intégration assets + polish UI
Outils :
Unity Canvas/UI Toolkit, GitHub

**- GD**
- Création niveaux + scripts d'événements
Outils :
Unity Timeline, prefabs, Notion (doc niveaux)

**- Artiste**
- Nouveaux environnements
- Effets visuels simples
Outils :
Blender, Aseprite, Unity Particle System

**- Sound**
- Musique d’ambiance 1 & 2
Outils :
FL Studio / LMMS, Reaper
Livrable : version jouable de 30 à 60 min.

### Mois 4 — Finalisation du contenu
**- Dev**
- Fonctionnalités secondaires
- Bugs majeurs
Outils :
Unity Profiler, GitHub Issues

**- Artiste**
- UI définitive
- Polissage
Outils :
Figma, Photoshop, Unity UI

**- GD**
- Ajustement du gameplay
- Tests internes
Outils :
Google Forms (retours internes), Excel (équilibrage)

**- Sound**
- Musiques finales
- Bruitages restants
Outils :
Reaper, Audacity

### Mois 5 — Optimisation + Test + Polish
**- Dev**
- Optimisation
- Correction de bugs
- Ajustement difficulté
Outils :
Unity Profiler, Deep Profiling, GitHub Projects

**- Artiste**
- Optimisation textures
- Petits effets visuels
Outils :
TexturePacker, Blender, Unity VFX

**- Sound**
- Mastering audio
Outils : Reaper

**- GD**
- Tests utilisateurs + corrections
Outils :
Playtests enregistrés, Google Forms, Notion

### Mois 6 — Finitions + Communication + Versions finales
**- Dev**
- Build final
- Compatibilité plateformes
Outils :
Unity Build Tools, itch.io or Steamworks

**- Artiste**
- Trailer du jeu
- Screenshots officiels
Outils :
Premiere Pro / DaVinci Resolve, OBS Studio

**- Sound**
- Mix final pour le trailer
Outils :
Reaper

**- GD**
- Dossier de présentation projet
Outils :
Canva, Google Slides, Notion
</details>

---

<details>
  <summary><h2>🎨 4. Liste complète d’assets graphiques à produire</h2></summary>
  
(Avec les outils pour chaque type)

**A. Personnages**
Modèle principal (Aseprite / Blender)
Animations : idle, marche, course, action (Aseprite ou Blender)

**B. Environnements**
Sols, arbres, rochers (Photoshop / Blender / Aseprite)
Météo (Unity Particle System)

**C. Objets**
Panneaux solaires, compost, outils (Illustrator / Aseprite)
Déchets (Aseprite)

**D. UI / Interface**
Icônes (Figma / Illustrator)
Boutons, HUD (Figma)

**E. Effets visuels**
Particules (Unity VFX / Particle System)
Transitions (Photoshop, Unity animations)
</details>

---

<details>
  <summary><h2>🕹️ 5. EXEMPLE DE DA</h2></summary>
    
# 🎨 Styles graphiques de jeux vidéo

## Styles 2D

### Pixel Art
| Style | Exemple visuel | Description |
|-------|----------------|-------------|
| **Pixel Art** | <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Celeste_screenshot_05.png" width="300"> | Pixelisé, rétro, inspiré des jeux 8–16 bits (ex : Celeste, Stardew Valley) |

---

### Vector Art / Flat Design
| Style | Exemple visuel | Description |
|-------|----------------|-------------|
| **Vector / Flat** | <img src="https://admin.itsnicethat.com/images/4BomiQz-gPjFAYlde7dX_DtUz-Q%3D/260534/format-webp%7Cwidth-2880/monument_valley_3_ustwo_games_digital_itsnicethat_MV3_KeyArt_4x5.png" width="300"> | Formes nettes, couleurs plates, style propre et minimaliste (ex : Monument Valley) |

---

### Hand-drawn / Dessiné à la main
| Style | Exemple visuel | Description |
|-------|----------------|-------------|
| **Hand-drawn** | <img src="https://game.info.intel.com/hs-fs/hubfs/07.%2010%20GAP%20Cuphead/Cuphead%20article/cuphead_screenshot_0002.png?name=cuphead_screenshot_0002.png&width=1920" width="300"> | Style illustratif ou cartoon dessiné à la main (ex : Cuphead, Ori) |

---

## Styles 3D

### Low Poly
| Style | Exemple visuel | Description |
|-------|----------------|-------------|
| **Low Poly** | <img src="https://www.openxcell.com/wp-content/uploads/2015/02/Low-poly-game-art-trends-and-exemplary-games.webp" width="300"> | Peu de polygones, rendu minimaliste et géométrique (ex : Poly Bridge) |

---

## Styles hybrides / expérimentaux

### Minimaliste / Abstract
| Style | Exemple visuel | Description |
|-------|----------------|-------------|
| **Minimaliste / Abstract** | <img src="https://readingatrecess.com/wp-content/uploads/2014/08/thomas_was_alone_screenshot.png" width="300"> | Formes simples, concept visuel épuré (ex : Journey, Thomas Was Alone) |

---

### Retro 3D (style PS1 / PS2)
| Style | Exemple visuel | Description |
|-------|----------------|-------------|
| **Retro 3D (PS1/PS2)** | <img src="https://i.ytimg.com/vi/ONueU-P8qPg/hq720.jpg" width="300"> | Textures low-res, modèles anguleux, rendu années 90 (ex : Paratopic) |

---

## Styles techniques

### Voxel Art
| Style | Exemple visuel | Description |
|-------|----------------|-------------|
| **Voxel Art** | <img src="https://d3kjluh73b9h9o.cloudfront.net/original/4X/5/4/f/54f197b07f39c7a2373ec82ca3754dc4f0d358f0.jpeg" width="300"> | Style en cubes volumétriques (ex : Minecraft, Trove) |

---

</details>

---
<details>
  <summary><h2>📘 6. GDD COMPLET (Game Design Document)</h2></summary>

**1 — Informations générales**
- Titre du jeu :
- Concept en une phrase :
- Genre : (gestion, puzzle, exploration…)
- Plateforme : PC / Mobile
- Durée totale de jeu :
- Public visé :
- Pourquoi le joueur joue ?
- Qu’est-ce qu’il apprend ?
- Quelle émotion tu veux transmettre ?

**2 — Pitch détaillé**
- Résumé du jeu (5 à 10 lignes)
- Thématique écologique centrale
- Objectif final du joueur

**3 — Boucle de gameplay**
- Le joueur explore un environnement
- Récupère des ressources / déchets
- Purifie / restaure la nature
- Débloque de nouvelles zones
- Progresse

**4 — Gameplay détaillé**
- Mécaniques principales :
- Déplacement
- Interactions
- Gestion des ressources
- Résolution de puzzles
- Améliorations
- Mécaniques secondaires :
- Objets à collecter
- Système écologique (croissance plantes, pollution…)

**5 — Progression du joueur**
- Niveau 1 :
- Niveau 2 :
- Niveau 3 :

**6 — Personnages**
- Description
- Objectifs / rôles
- Animations nécessaires

**7 — Environnements**
- Zones du jeu
- Thème visuel
- Interactions possibles
- Cycle jour/nuit

**8 — Interface (UI/UX)**
- HUD
- Menus
- Indicateurs visuels
- Feedbacks (sons, couleurs, vibrations)

**9 — Éléments artistiques**
- Style graphique
- Palette de couleurs
- Références artistiques
- Modèles 2D / 3D nécessaires

**10 — Éléments sonores**
- Ambiances
- Bruitages
- Musiques
- Feedback audio

**11 — Technologies utilisées**
- Moteur (Unity)
- Gestion de version (GitHub / GitLab)
- Logiciels (Blender, Aseprite, Audacity…)

**12 — Risques + solutions**
- Retard : réduire les niveaux
- Trop d’assets : passer au style lowpoly
- Bugs : focus sur gameplay simple
</details>
