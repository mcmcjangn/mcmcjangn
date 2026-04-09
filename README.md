<div align="center">

```
███╗   ███╗ ██████╗███╗   ███╗ ██████╗     ██╗ █████╗ ███╗   ██╗ ██████╗ ███╗   ██╗
████╗ ████║██╔════╝████╗ ████║██╔════╝     ██║██╔══██╗████╗  ██║██╔════╝ ████╗  ██║
██╔████╔██║██║     ██╔████╔██║██║          ██║███████║██╔██╗ ██║██║  ███╗██╔██╗ ██║
██║╚██╔╝██║██║     ██║╚██╔╝██║██║     ██   ██║██╔══██║██║╚██╗██║██║   ██║██║╚██╗██║
██║ ╚═╝ ██║╚██████╗██║ ╚═╝ ██║╚██████╗╚█████╔╝██║  ██║██║ ╚████║╚██████╔╝██║ ╚████║
╚═╝     ╚═╝ ╚═════╝╚═╝     ╚═╝ ╚═════╝ ╚════╝ ╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝ ╚═╝  ╚═══╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=16&pause=1000&color=39D353&center=true&vCenter=true&width=500&lines=Game+Developer+%7C+UE5+%7C+Blender;Blueprint+Architect+%F0%9F%9A%80;Crafting+worlds%2C+one+node+at+a+time.)](https://git.io/typing-svg)

</div>

---

## `$ whoami`

```yaml
name     : mcmcjangn
role     : Game Dev Student
location : Seoul, KR 🇰🇷
focus    : Unreal Engine 5 · Blender · Blueprint Visual Scripting
status   : [ open to collaborations ]
```

> Building smooth 3D systems — spline-based aircraft, procedural motion,  
> and everything that makes a game *feel* right.

---

## `$ cat tech_stack.txt`

**Engine & Tools**

![Unreal Engine](https://img.shields.io/badge/Unreal%20Engine%205-0E1128?style=for-the-badge&logo=unrealengine&logoColor=white)
![Blender](https://img.shields.io/badge/Blender-E87D0D?style=for-the-badge&logo=blender&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)

**Pipeline**

![FBX](https://img.shields.io/badge/FBX%20Pipeline-888?style=for-the-badge)
![glTF](https://img.shields.io/badge/glTF%2FglB-85BB65?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## `$ highlight --project airborne`

```cpp
// Catmull-Rom spline movement — arc-length parameterized
// Airbus A310 mesh · UE5 Blueprint implementation

FVector GetSmoothedPosition(float NormalizedT) {
    float ArcT   = SampleArcLength(Spline, NormalizedT);
    FVector  Pos = Spline->GetLocationAtTime(ArcT, ESplineCoordinateSpace::World);
    FRotator Rot = UKismetMathLibrary::FindLookAtRotation(Pos, NextPos);
    return   FMath::RInterpTo(CurrentRot, Rot, DeltaTime, 4.5f);
}
// Result: zero jitter · smooth zone transitions · consistent speed ✓
```

---

## `$ git log --stat`

<div align="center">

![mcmcjangn's GitHub Stats](https://github-readme-stats.vercel.app/api?username=mcmcjangn&show_icons=true&theme=github_dark&hide_border=true&title_color=39d353&icon_color=58a6ff&text_color=c9d1d9&bg_color=0d1117)

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=mcmcjangn&layout=compact&theme=github_dark&hide_border=true&title_color=39d353&text_color=c9d1d9&bg_color=0d1117)

</div>

---

## `$ cat contribution_graph`

<div align="center">

![GitHub Activity Graph](https://github-readme-activity-graph.vercel.app/graph?username=mcmcjangn&theme=github-compact&hide_border=true&color=39d353&line=39d353&point=58a6ff&area=true&area_color=39d35320)

</div>

---

<div align="center">

```
┌─────────────────────────────────────────┐
│  "Make it move like it means it."       │
│                        — mcmcjangn     │
└─────────────────────────────────────────┘
```

![Visitor Count](https://komarev.com/ghpvc/?username=mcmcjangn&color=39d353&style=flat-square&label=visitors)

</div>
