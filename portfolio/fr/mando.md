# Mando Productions (2010–2016) – Fabien Simon

[← Accueil du portfolio](../fr.md) · [English version](../en/mando.md) · [Mes crédits sur MobyGames](https://www.mobygames.com/person/759004/fabien-simon/)

**Lead Dev, juin 2010 – avril 2016.** Studio de jeux vidéo : jeux Unity et mobiles, consoles, réalité virtuelle et R&D (réalité augmentée, vision sur mobile). J'y ai encadré des équipes de 1 à 7 personnes, en travaillant main dans la main avec les game designers.

![Unity](https://img.shields.io/badge/Unity-000000?logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-512BD4?logo=dotnet&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?logo=cplusplus&logoColor=white)
![Objective-C](https://img.shields.io/badge/Objective--C-438EFF?logo=apple&logoColor=white)
![ShiVa](https://img.shields.io/badge/ShiVa_engine-555555)
![iOS](https://img.shields.io/badge/iOS-000000?logo=apple&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?logo=android&logoColor=white)
![PS3](https://img.shields.io/badge/PS3-003791?logo=playstation&logoColor=white)
![Xbox 360](https://img.shields.io/badge/Xbox_360-107C10?logo=xbox&logoColor=white)
![Oculus Rift](https://img.shields.io/badge/Oculus_Rift-1C1E20?logo=oculus&logoColor=white)
![WPF](https://img.shields.io/badge/WPF_/_XAML-555555)

### En chiffres
| | |
|---|---|
| 📲 | **1 à 3 millions** de téléchargements cumulés sur les jeux mobiles |
| 🥽 | ***Babel Rising 3D*** : dans le lineup des **10 premiers jeux du store Oculus Rift** |
| 🎮 | ***Babel Rising 3D*** sorti sur **PS3** (PS Move) et **Xbox 360** (Kinect), porté sur PC, Mac et iOS |
| 👥 | Équipes de **1 à 7 personnes** |

### *Babel Rising 3D* : consoles et réalité virtuelle

<img src="../../assets/mando/babel-rising-3d.png" alt="Babel Rising 3D" width="420" />

- Développé avec le moteur **ShiVa**
- Sorti sur **PS3** (conformité **Sony TRC**, **PS Move**) et **Xbox 360** (**Kinect**)
- Portages **PC, Mac et iOS**
- Crédité *Programming* · [fiche MobyGames](https://www.mobygames.com/game/57700/babel-rising-3d/)

<img src="../../assets/diagrams/babel-platforms-fr.svg" alt="Plateformes de Babel Rising 3D" />

#### Portage sur Oculus Rift (DK1 puis DK2)
Le jeu faisait partie du lineup des 10 premiers jeux du store Oculus. Le SDK d'origine était très bas niveau : presque tout a été fait à la main.
- **Intégration du SDK à la main en C++** dans le moteur
- **Rendu stéréo** et **shader de distorsion des lentilles** écrits à la main
- **Head tracking** : lecture des capteurs d'orientation et application à la caméra
- Travail sur la **latence** et le **framerate** pour limiter le mal des transports

<img src="../../assets/diagrams/oculus-pipeline-fr.svg" alt="Chaîne de rendu VR sur Oculus Rift" />

### Jeux Unity (C#)

<img src="../../assets/mando/hills-of-glory-3d.webp" alt="Hills of Glory 3D" width="130" align="right" />

- ***Hills of Glory 3D*** : iOS, Android, PC, Mac · crédité *Programming* · [fiche MobyGames](https://www.mobygames.com/game/126860/hills-of-glory-3d/)
- ***Babel Casino*** : jeu Facebook
- ***Runner Ocean's Run*** : jeu mobile, partie réseau social avec intégration du **SDK Facebook**
- Plusieurs **serious games** pour des entreprises et des associations
- Divers prototypes

<img src="../../assets/mando/hills-of-glory-3d-screen.png" alt="Hills of Glory 3D, capture d'écran" width="420" />

### Applications mobiles et SDK
#### *Strip Messenger*

<img src="../../assets/mando/strip-messenger.jpg" alt="Strip Messenger" width="420" />

- Application **iOS native** (iOS SDK, **Objective-C**) : messagerie instantanée qui transforme les conversations en bandes dessinées
- Chaque utilisateur crée son avatar ; les messages s'affichent dans des bulles et les emojis deviennent des expressions du personnage
- Fonctions spécifiques à l'iPhone : caméra, carnet d'adresses, interface clavier
- L'application est ensuite devenue *Striply* (startup de la French Tech Los Angeles) · [fiche Les Pépites Tech](https://lespepitestech.com/startup-de-la-french-tech/strip-messenger)

#### SDK mobiles
- **SDK d'achats in-app iOS** intégré puis déployé sur **tous les jeux du studio**
- **SDK Facebook**
- Nombreux SDK mobiles : achats in-app, leaderboards, réseaux sociaux, régies publicitaires (Java pour certains SDK)

### R&D : réalité augmentée, vision et réalité virtuelle
- **Vérification de billets de banque par détection d'hologramme** sur mobile (billets d'un pays étranger)
- **Scan AR d'étiquettes de rhum de luxe** pour vérifier leur authenticité
- Réalité augmentée sur mobile : lecture de **QR codes** par la caméra
- R&D sur **casques VR** : prototypes, visites virtuelles, photos 360° et 3D

#### *Visiwyg* : pré-visites immobilières en réalité virtuelle
- Solution clé en main pour la société 2VR, cliente de Mando : appareil photo 360° sur trépied, casques de réalité virtuelle (Samsung Gear VR) et logiciel
- Le client visite le logement dans le casque, pendant que le conseiller commente la visite depuis un écran de contrôle
- Points d'intérêt (cheminée, jardin…) et plan du logement accessible en baissant la tête
- Les conseillers construisent eux-mêmes une visite en un quart d'heure, grâce à une application web
- **J'ai développé l'ensemble** : application du casque, écran de contrôle du conseiller et application web de construction des visites (**WPF, XAML**)
- Utilisée fin 2015 par Nexity dans sa première « agence connectée » (Paris 5e) · articles [Clubic](https://www.clubic.com/pro/actualite-e-business/article-786284-1-visitez-nouvel-appartement-3d.html) et [Magazine Expression](https://www.magazineexpression.fr/Guides/Tendance/numerique-le-secteur-immobilier-poursuit-sa-transformation-2950)

### Ce que j'en retiens
- **Passage à Unity et au C#**, devenu ma techno principale pendant 15 ans
- **Contraintes consoles** : certification Sony (TRC) sur PS3, sortie Xbox 360
- **VR des débuts** : un SDK bas niveau intégré à la main, rendu stéréo et lutte contre la latence
- **Mobile à grande échelle** : millions de téléchargements, SDK de monétisation déployés sur tout le catalogue
- **R&D appliquée** : vision par ordinateur et réalité augmentée sur mobile

### Récapitulatif par plateforme
| Plateforme | Projets | Technos |
|---|---|---|
| iOS | *Hills of Glory 3D*, *Strip Messenger*, portage *Babel Rising 3D*, jeux mobiles | Unity C#, Objective-C, SDK in-app |
| Android | *Hills of Glory 3D*, jeux mobiles | Unity C#, Java (SDK) |
| PC, Mac | *Hills of Glory 3D*, portages *Babel Rising 3D* | Unity C#, ShiVa |
| PS3 | *Babel Rising 3D* | ShiVa, Sony TRC, PS Move |
| Xbox 360 | *Babel Rising 3D* | ShiVa, Kinect |
| VR | *Babel Rising 3D* sur Oculus Rift, *Visiwyg*, prototypes | C++, WPF / XAML |
| Facebook | *Babel Casino* | Unity C#, SDK Facebook |

[← Période précédente : White Birds Productions (2005–2010)](white-birds.md) · Période suivante : [Your Data Consulting (2016–2019) →](your-data.md)

## Références
Crédits publics sur MobyGames :
- [Profil de Fabien Simon sur MobyGames](https://www.mobygames.com/person/759004/fabien-simon/)
- [*Babel Rising 3D*](https://www.mobygames.com/game/57700/babel-rising-3d/) (2012) : Programming
- [*Hills of Glory 3D*](https://www.mobygames.com/game/126860/hills-of-glory-3d/) (2013) : Programming


Dans la presse :
- [Strip Messenger, Les Pépites Tech](https://lespepitestech.com/startup-de-la-french-tech/strip-messenger)
- [Visiwyg chez Nexity, Clubic (décembre 2015)](https://www.clubic.com/pro/actualite-e-business/article-786284-1-visitez-nouvel-appartement-3d.html)
- [Visiwyg, Magazine Expression (janvier 2016)](https://www.magazineexpression.fr/Guides/Tendance/numerique-le-secteur-immobilier-poursuit-sa-transformation-2950)

---
<sub>Visuels issus de MobyGames et de Les Pépites Tech. Marques et illustrations appartenant à leurs ayants droit.</sub>
