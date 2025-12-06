# Projet de Jeu Vidéo Écologique

---

<details>
  <summary><h2>👨‍💻 1. Répartition des rôles</h2></summary>

**Répartition des rôles**
- Game Designer (GD) :[Yanis Perez Assim Sanchez Penas] 
- Dev 1 (Gameplay) [Elouan Maisonette ]
- Dev 2 (Tech/UI) [Tasnime El Ouestlati]
- Artiste [Thinhinane Goucem]
- Sound Designer [Yanis Perez Assim Sanchez Penas]
</details>

---

<details>
  <summary><h2>📆 1. PLANNING PAR RÔLE ET TÂCHES COMMUNES</h2></summary>
  
| Rôle | Tâches | Outils / Applications |
|------|--------|--------------------|
| **Game Designer (GD)** | - Document du concept<br>- Cahier des charges + boucle de gameplay<br>- Croquis des niveaux (maquettes UI sur Figma)<br>- Level design des 2 premiers niveaux<br>- Création des niveaux + scripts d’événements<br>- Ajustement du gameplay<br>- Tests internes (collecter les retours)<br>- Tests utilisateurs + corrections<br>- Dossier de présentation du projet | Notion, Google Docs, Figma, Unity Tilemap (2D), Google Sheets (équilibrage), Unity Timeline, Google Forms, Excel, Canva, Google Slides |
| **Dev 1 (Gameplay Programmer)** | - Prototype minimal (déplacements, interactions)<br>- Programmation des mécaniques de base<br>- Collisions, inventaire, interactions<br>- IA basique<br>- Feedbacks (retours visuels/sons liés au gameplay)<br>- Fonctionnalités secondaires<br>- Correction des bugs majeurs<br>- Optimisation du gameplay<br>- Ajustement de la difficulté | Unity, C#, Visual Studio Code, Unity Collisions 2D/3D, Unity NavMesh (IA si 3D), Unity Profiler, Deep Profiling |
| **Dev 2 (Tech / UI Programmer)** | - Mise en place du projet (Unity)<br>- Gestion des inputs + caméras<br>- UI de base (menus, HUD)<br>- Système de sauvegarde (JSON, PlayerPrefs)<br>- Intégration des assets artistiques<br>- Polish UI<br>- Fonctionnalités secondaires tech<br>- Correction de bugs<br>- Optimisation technique<br>- Build final + compatibilité plateformes | Unity, Unity Input System, Unity UI Toolkit / Canvas, Figma (UI mockups fournis par GD), JSON / PlayerPrefs, Unity Profiler, Unity Build Tools, itch.io / Steamworks |
| **Artiste (2D/3D)** | - Tests de style graphique<br>- Concept arts<br>- Premiers assets simples<br>- Création des assets principaux<br>- Animations simples<br>- Nouveaux environnements<br>- Effets visuels simples<br>- UI définitive (style visuel + icons)<br>- Polissage graphique<br>- Optimisation textures<br>- Petits effets visuels<br>- Trailer du jeu<br>- Screenshots officiels | Aseprite (2D), Photoshop, Blender (3D, animations), Unity Particle System, TexturePacker, Unity VFX, Premiere Pro, OBS Studio |
| **Sound Designer** | - Recherches sonores + ambiance générale<br>- Bruitages de base (pas, objets, interface)<br>- Musique d’ambiance<br>- Musiques finales<br>- Bruitages restants<br>- Mastering audio<br>- Mix final pour le trailer | YouTube Audio Library, Audacity, Reaper, freesound.org, FL Studio|

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

| Style | Image | Description |
|-------|--------|-------------|
| **Pixel Art** | <img src="https://images.gamebanana.com/img/ss/mods/6427b7f0c3f2d.jpg" width="180"> | Pixelisé, rétro, inspiré 8–16 bits (Celeste) |
| **Vector Art** | <img src="https://i.redd.it/steam-page-updated-v0-cu134okpskkf1.jpg?width=2560&format=pjpg&auto=webp&s=c8f235e9a9d3f2ba601ff28951e5ea1ab480f346" width="180"> | Formes géométriques nettes, lignes et courbes vectorielles (Hollow Knight) |
| **Flat Design** | <img src="https://static0.polygonimages.com/wordpress/wp-content/uploads/chorus/uploads/chorus_asset/file/3400436/a02_Chasm.0.png?q=50&fit=crop&w=825&dpr=1.5" width="180"> | Minimaliste, couleurs uniformes et surfaces plates (Alto’s Adventure) |
| **Paper-cut / Paper Craft** | <img src="https://i.redd.it/any-recommendations-for-games-similar-to-paper-mario-or-v0-fuwcse65c5if1.jpg?width=1920&format=pjpg&auto=webp&s=2ff6b9aab5da926d12829d724ce491a7d7ef1c4c" width="180"> | Style papier découpé ou collage (Paper Mario) |
| **Hand-drawn / Dessiné à la main** | <img src="https://assetsio.gnwcdn.com/ilustracja_2_woda.jpg.jpg?width=690&quality=85&format=jpg&dpr=1.5&auto=webp" width="180"> | Style illustratif ou cartoon dessiné à la main (Ori and the Blind Forest) |
| <span style="background:#4CAF50; padding:4px; border-radius:4px;">Pixel Art</span> | <img src="https://shared.akamai.steamstatic.com/store_item_assets/steam/apps/1625450/ss_93ca2a0fe35660aa6ff3cf5c512a10c32ab621e2.1920x1080.jpg?t=1625163481" width="180"> | Peu de polygones, style géométrique minimaliste (Muck) |
| **Minimaliste / Abstract** | <img src="https://i.jeuxactus.com/datas/jeux/j/o/journey/xl/journey-4e2657dc83581.jpg" width="180"> | Formes simples et stylisées (Journey) |
| **Retro 3D (PS1/PS2)** | <img src="https://www.pcgamesn.com/wp-content/sites/pcgamesn/legacy/Back_in_1995.jpg" width="180"> | Effet low-res, textures floues (Back in 1995) |
| **Voxel Art** | <img src="https://game-guide.fr/wp-content/uploads/2017/03/TrovePS4_01.jpg" width="180"> | Graphismes en cubes volumétriques (Trove) |
</details>

---

  <summary><h2>📘 6. Game Design Document et digramme de GANTT</h2></summary>

[GDD.pdf](https://github.com/user-attachments/files/24003493/GDD.pdf)


[Gantt Excel.xlsx](https://github.com/user-attachments/files/24003313/Gantt.Excel.xlsx)
