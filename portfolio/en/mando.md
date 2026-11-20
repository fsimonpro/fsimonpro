# Mando Productions (2010–2016) – Fabien Simon

[← Portfolio home](../en.md) · [Version française](../fr/mando.md) · [My MobyGames credits](https://www.mobygames.com/person/759004/fabien-simon/)

**Lead Dev, June 2010 – April 2016.** Video game studio: Unity and mobile games, consoles, virtual reality and R&D (augmented reality, mobile computer vision). I led teams of 1 to 7 people, working hand in hand with the game designers.

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

### Key figures
| | |
|---|---|
| 📲 | **1 to 3 million** cumulative downloads on the mobile games |
| 🥽 | ***Babel Rising 3D***: part of the **launch lineup of the first 10 games on the Oculus Rift store** |
| 🎮 | ***Babel Rising 3D*** released on **PS3** (PS Move) and **Xbox 360** (Kinect), ported to PC, Mac and iOS |
| 👥 | Teams of **1 to 7 people** |

### *Babel Rising 3D*: consoles and virtual reality

<img src="../../assets/mando/babel-rising-3d.png" alt="Babel Rising 3D" width="420" />

- Built with the **ShiVa** engine
- Released on **PS3** (**Sony TRC** compliance, **PS Move**) and **Xbox 360** (**Kinect**)
- Ported to **PC, Mac and iOS**
- Credited *Programming* · [MobyGames page](https://www.mobygames.com/game/57700/babel-rising-3d/)

```mermaid
flowchart LR
    S(("<b>Babel Rising 3D</b><br/>ShiVa engine")) --> PS3["PS3<br/>Sony TRC, PS Move"]
    S --> X["Xbox 360<br/>Kinect"]
    S --> O["Oculus Rift<br/>DK1 then DK2"]
    S --> P["PC, Mac, iOS"]
```

#### Oculus Rift port (DK1 then DK2)
The game was part of the first 10 games on the Oculus store. The original SDK was very low level, so almost everything was done by hand.
- **Hand-integrated the SDK in C++** into the engine
- **Stereo rendering** and **lens distortion shader** written by hand
- **Head tracking**: reading the orientation sensors and applying them to the camera
- Worked on **latency** and **frame rate** to limit motion sickness

```mermaid
flowchart LR
    C["Orientation sensors<br/>(head tracking)"] --> CAM["Game camera"]
    CAM --> ST["Stereo rendering<br/>left eye / right eye"]
    ST --> D["Lens distortion<br/>shader"]
    D --> R["Oculus Rift headset"]
```

### Unity games (C#)

<img src="../../assets/mando/hills-of-glory-3d.webp" alt="Hills of Glory 3D" width="130" align="right" />

- ***Hills of Glory 3D***: iOS, Android, PC, Mac · credited *Programming* · [MobyGames page](https://www.mobygames.com/game/126860/hills-of-glory-3d/)
- ***Babel Casino***: Facebook game
- ***Runner Ocean's Run***: mobile game, social features with **Facebook SDK** integration
- Several **serious games** for companies and non-profits
- Various prototypes

<img src="../../assets/mando/hills-of-glory-3d-screen.png" alt="Hills of Glory 3D screenshot" width="420" />

### Mobile apps and SDKs
- ***Strip Messenger***: **native iOS** app (iOS SDK, **Objective-C**), real-time comic-strip style messaging; iPhone-specific features: camera, address book, keyboard interface
- **iOS in-app purchase SDK** integrated, then rolled out to **every game of the studio**
- **Facebook SDK**
- Many mobile SDKs: in-app purchases, leaderboards, social networks, ad networks (Java for some SDKs)

### R&D: augmented reality, computer vision and virtual reality
- **Banknote verification through hologram detection** on mobile (banknotes from a foreign country)
- **AR scanning of luxury rum labels** to check their authenticity
- Mobile augmented reality: **QR code** reading through the camera
- R&D on **VR headsets**: prototypes, virtual tours, 360° and 3D photos
- ***Visiwyg***: home tour solution on VR headsets and on the web (**WPF, XAML**)

### Takeaways
- **Move to Unity and C#**, which became my main technology for 15 years
- **Console constraints**: Sony certification (TRC) on PS3, Xbox 360 release
- **Early-days VR**: a low-level SDK integrated by hand, stereo rendering and fighting latency
- **Mobile at scale**: millions of downloads, monetization SDKs rolled out across the whole catalog
- **Applied R&D**: computer vision and augmented reality on mobile

### Summary by platform
| Platform | Projects | Tech |
|---|---|---|
| iOS | *Hills of Glory 3D*, *Strip Messenger*, *Babel Rising 3D* port, mobile games | Unity C#, Objective-C, in-app SDK |
| Android | *Hills of Glory 3D*, mobile games | Unity C#, Java (SDKs) |
| PC, Mac | *Hills of Glory 3D*, *Babel Rising 3D* ports | Unity C#, ShiVa |
| PS3 | *Babel Rising 3D* | ShiVa, Sony TRC, PS Move |
| Xbox 360 | *Babel Rising 3D* | ShiVa, Kinect |
| VR | *Babel Rising 3D* on Oculus Rift, *Visiwyg*, prototypes | C++, WPF / XAML |
| Facebook | *Babel Casino* | Unity C#, Facebook SDK |

[← Previous period: White Birds Productions (2005–2010)](white-birds.md) · Next period: [Your Data Consulting (2016–2019) →](your-data.md)

## References
Public credits on MobyGames:
- [Fabien Simon's MobyGames profile](https://www.mobygames.com/person/759004/fabien-simon/)
- [*Babel Rising 3D*](https://www.mobygames.com/game/57700/babel-rising-3d/) (2012): Programming
- [*Hills of Glory 3D*](https://www.mobygames.com/game/126860/hills-of-glory-3d/) (2013): Programming

---
<sub>Images from MobyGames. Trademarks and artwork belong to their respective owners.</sub>
