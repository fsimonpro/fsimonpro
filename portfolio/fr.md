# Portfolio détaillé – Fabien Simon

🇬🇧 [English version](en.md) · [← Retour au profil](../README.md)

Tech Lead Fullstack .NET / C# & IA, plus de 20 ans de développement logiciel, dont 11 ans dans le jeu vidéo (2005–2016).

## Sommaire
- [White Birds Productions (2005–2010)](#white-birds-productions-20052010)
- *À venir : Mando Productions (2010–2016), Your Data Consulting (2016–2019), Manzalab (2019–2026), formation*

---

## White Birds Productions (2005–2010)

<img src="https://upload.wikimedia.org/wikipedia/fr/8/89/White_Birds_Production_Logo.png" alt="White Birds Productions" height="80" />

Studio de jeux vidéo (notamment jeux d'aventure et point & click). J'y suis entré en stage de fin d'études, puis j'y suis resté 5 ans : développeur junior, puis Lead Dev à partir de 2007.

```mermaid
flowchart LR
    A["<b>2005</b><br/>Stage de fin d'études<br/>gameplay Lua sur <i>Paradise</i>"] --> B["<b>2005 – 2007</b><br/>Développeur junior<br/>point & click, outils, moteur PlayAll"]
    B --> C["<b>2007 – 2010</b><br/>Lead Dev<br/>PC, Nintendo DS, Wii, iPhone / iPad"]
```

![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![Lua](https://img.shields.io/badge/Lua-2C2D72?logo=lua&logoColor=white)
![HLSL](https://img.shields.io/badge/HLSL-555555)
![MFC](https://img.shields.io/badge/MFC-555555)
![Xcode](https://img.shields.io/badge/Xcode-147EFB?logo=xcode&logoColor=white)
![Nintendo DS](https://img.shields.io/badge/Nintendo_DS-E60012?logo=nintendo&logoColor=white)
![Wii](https://img.shields.io/badge/Wii-8B8B8B?logo=wii&logoColor=white)
![iOS](https://img.shields.io/badge/iPhone_/_iPad-000000?logo=apple&logoColor=white)

### En chiffres
| | |
|---|---|
| 🏆 | ***Nikopol*** : prix du meilleur graphisme aux **Milthon 2008** (Festival du jeu vidéo) |
| 📱 | ***Cardboard Castle*** : **top 5 App Store France** |
| 🎮 | Jeux livrés sur **5 plateformes** : PC, Nintendo DS, Nintendo Wii, iPhone, iPad |
| 👥 | Équipe jusqu'à **5 personnes** sur *Aztec Treasure Hunt* (3 intégrateurs, 1 codeur moteur, 1 codeur gameplay) |

### Lead Dev (2007 – mai 2010)

#### *Nikopol* (PC), prix du meilleur graphisme aux Milthon 2008

<img src="https://upload.wikimedia.org/wikipedia/en/e/e6/Nikopol_Secrets_of_the_Immortals_cover_art.jpg" alt="Nikopol" width="130" align="right" />

- Outil d'export des « warps » pour la vue à 360° (**C++ / MFC**)
- Programmation du gameplay en **Lua**
- Effets spéciaux en **pixel shaders HLSL**
- Mise en place de l'équipe et du pipeline de production avec un studio externe (**MZone**)

```mermaid
flowchart LR
    M["Équipe + pipeline<br/>avec le studio externe MZone"] --> N
    E["Outil d'export des warps<br/>C++ / MFC"] --> V["Vue à 360°"]
    G["Gameplay<br/>Lua"] --> N(("<b>Nikopol</b>"))
    S["Effets spéciaux<br/>pixel shaders HLSL"] --> N
    V --> N
```

#### *Kate Brooks' Adventure*, jeu d'objets cachés cross-platform
- Jeu PC d'objets cachés en trois chapitres, décliné sur Wii, iPad et iPhone
- Mise en place de l'équipe et du pipeline

```mermaid
flowchart LR
    PC["<b>PC</b><br/>3 chapitres"] --> Wii
    PC --> iPad
    PC --> iPhone
```

#### Nintendo DS
- ***Let's Play Fashion Designer*** : gestion de projet jusqu'à la livraison, développement en **C** avec une mémoire de **256 Ko** (gestion fine de la mémoire)
- ***Tower Defense*** : affichage isométrique, pathfinding
- ***Nikopol DS*** : affichage à 360° sur DS
- Prototype de jeu d'énigmes 2D façon *Professeur Layton* (**C++**)

#### Nintendo Wii : *Aztec Treasure Hunt*
- Point & click 2D avec des outils en 3D
- Gestion des **TRC Wii** (exigences de certification de Nintendo)
- Équipe de 5 : 3 intégrateurs, 1 codeur moteur, 1 codeur gameplay

#### iPhone / iPad
- ***Cardboard Castle*** (**Xcode + Lua**) : top 5 App Store France
- ***Last King of Africa*** : adaptation de *Paradise*

### Développeur junior (mai 2005 – octobre 2007)

#### Stage de fin d'études (mai – septembre 2005) : *Paradise*

<img src="https://upload.wikimedia.org/wikipedia/en/7/7c/Paradise_PC.jpg" alt="Paradise" width="130" align="right" />

- Programmation du gameplay en **Lua** sur le moteur 2D/3D maison **Opalium** (programmation objet et événementielle)
- Mini-jeu de pêche (inertie, mouvements aléatoires), caméras qui suivent un personnage
- Travail avec des sous-traitants slovènes via un gestionnaire de sources

#### Jeux point & click
- ***Paradise*** et ***Martine 1 & 2*** (jeux ludo-éducatifs) : moteur maison, scripts **Lua**

#### Outils et moteur
- Outils d'export d'assets en **C++** et pipelines de production
- Participation au moteur 3D multiplateforme ***PlayAll*** (PS3, Xbox 360, PC, C++), commun à plusieurs entreprises ; prototype d'un système de point & click

### Ce que j'en retiens
- **Travail étroit avec les game designers**, énormément sur les jeux d'aventure
- **Contraintes matérielles fortes** : 256 Ko de mémoire sur DS, certification Nintendo (TRC Wii)
- **Production multiplateforme** : un même jeu décliné sur PC, Wii, iPad et iPhone
- **Premiers rôles de lead** : constitution d'équipes, pipelines avec des studios externes, gestion de projet jusqu'à la livraison

### Récapitulatif par plateforme
| Plateforme | Jeux | Technos |
|---|---|---|
| PC | *Paradise*, *Martine 1 & 2*, *Nikopol*, *Kate Brooks' Adventure* | Moteur maison, Lua, C++ / MFC, HLSL |
| Nintendo DS | *Let's Play Fashion Designer*, *Tower Defense*, *Nikopol DS*, prototype d'énigmes | C, C++ |
| Nintendo Wii | *Aztec Treasure Hunt*, *Kate Brooks' Adventure* | TRC Wii |
| iPhone / iPad | *Cardboard Castle*, *Last King of Africa*, *Kate Brooks' Adventure* | Xcode, Lua |
| PS3, Xbox 360, PC | Moteur *PlayAll* (participation) | C++ |

---
<sub>Visuels : logo et jaquettes issus de Wikipédia ; marques et illustrations appartenant à leurs ayants droit.</sub>
