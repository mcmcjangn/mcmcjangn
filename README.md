<div align="center">

```
███╗   ███╗██╗███╗   ██╗ ██████╗██╗  ██╗ █████╗ ███████╗
████╗ ████║██║████╗  ██║██╔════╝██║  ██║██╔══██╗██╔════╝
██╔████╔██║██║██╔██╗ ██║██║     ███████║███████║█████╗  
██║╚██╔╝██║██║██║╚██╗██║██║     ██╔══██║██╔══██║██╔══╝  
██║ ╚═╝ ██║██║██║ ╚████║╚██████╗██║  ██║██║  ██║███████╗
╚═╝     ╚═╝╚═╝╚═╝  ╚═══╝ ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&pause=1000&color=39D353&center=true&vCenter=true&width=520&lines=Still+learning.+Always+building.;Game+Dev+%7C+Server+%7C+Web+%7C+UE5;Looking+for+opportunities+overseas+%F0%9F%9A%80)](https://git.io/typing-svg)

</div>

---

## `$ whoami`

```yaml
name      : Minchae
handle    : mcmcjangn
location  : Seoul, KR 🇰🇷
status    : University student — still learning, still shipping
current   : Deep in Unreal Engine 5
goal      : Land a game dev role overseas someday
```

> I don't specialize in one thing — I build across game servers, web backends,
> and game clients. Every project teaches me something new.
> Right now? It's all about UE5.

---

## `$ git log --oneline --timeline`

```
2023.03 – 2024.03  ●  President @ ICON (university dev club)
2024.03 – 2024.06  ●  Built a game from scratch using C++
2024               ●  UMC 6th — Server Development track
2025 – present     ●  Studying Unreal Engine 5 (ongoing)
```

### 🟡 2023.03 – 2024.03 &nbsp;·&nbsp; President @ ICON

Led a university developer community as club president.  
Organized study sessions, managed members, and set the direction for team projects.

`leadership` `community` `planning`

---

### 🟠 2024.03 – 2024.06 &nbsp;·&nbsp; Game Development in C++

Designed and implemented a game from the ground up using C++.  
Covered core systems: game loop, collision detection, state management, and input handling.

`C++` `game dev` `systems programming`

---

### 🔵 2024 &nbsp;·&nbsp; UMC 6th — Server Development

Participated in UMC (University MakeUs Challenge) 6th cohort as a server developer.  
Worked in a cross-functional team through full deployment of a real service.

🔗 [PM Day Project — Notion](https://imminent-mail-488.notion.site/PM-Day-faab0c35544d42dfbf9bc562977b8c8b)

`server` `backend` `team project` `deployment`

---

### 🟢 2025 – Present &nbsp;·&nbsp; Unreal Engine 5 &nbsp;● *now*

Currently going deep on UE5 Blueprint Visual Scripting and 3D pipelines.  
Working on a spline-based aircraft movement system with smooth arc-length parameterization.

`UE5` `Blender` `Blueprint` `C++` `game client`

---

## `$ cat current_work.cpp`

```cpp
// Aircraft spline movement — arc-length parameterized
// Airbus A310 mesh · UE5 Blueprint implementation

void AircraftMovement::Tick(float DeltaTime) {
    float    T   = SampleArcLength(Spline, Progress);
    FVector  Pos = Spline->GetLocationAtTime(T, ESplineCoordinateSpace::World);
    FRotator Rot = UKismetMathLibrary::FindLookAtRotation(Pos, NextPos);

    Aircraft->SetActorRotation(
        FMath::RInterpTo(CurrentRot, Rot, DeltaTime, 4.5f)
    ); // zero jitter · smooth zone transitions ✓
}
```

---

## `$ ls tech/`

**Game Dev**

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine%205-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Backend / Server**

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

---

## `$ cat goals.txt`

```
▸ No single specialization — broad by choice, deep where it matters
▸ Game server · web backend · game client — done all three, want more
▸ Currently going deep on UE5 and game client development
▸ Actively looking for overseas opportunities in the game industry
▸ One thing stays constant: I'm still learning
```

---

## `$ git log --stat`

<div align="center">

![Minchae's GitHub Stats](https://github-readme-stats.vercel.app/api?username=mcmcjangn&show_icons=true&theme=github_dark&hide_border=true&title_color=39d353&icon_color=58a6ff&text_color=c9d1d9&bg_color=0d1117)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mcmcjangn&layout=compact&theme=github_dark&hide_border=true&title_color=39d353&text_color=c9d1d9&bg_color=0d1117)

</div>

---

## `$ cat contribution_graph`

<div align="center">

![Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=mcmcjangn&theme=github-compact&hide_border=true&color=39d353&line=39d353&point=58a6ff&area=true)

</div>

---

<div align="center">

```
┌──────────────────────────────────────────────────┐
│  "I don't know everything. That's the point."    │
│                                   — Minchae      │
└──────────────────────────────────────────────────┘
```

![](https://komarev.com/ghpvc/?username=mcmcjangn&color=39d353&style=flat-square&label=profile+views)

</div>
