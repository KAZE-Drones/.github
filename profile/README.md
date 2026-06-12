<div align="center">

<br>

```
██╗  ██╗ █████╗ ███████╗███████╗
██║ ██╔╝██╔══██╗╚══███╔╝██╔════╝
█████╔╝ ███████║  ███╔╝ █████╗  
██╔═██╗ ██╔══██║ ███╔╝  ██╔══╝  
██║  ██╗██║  ██║███████╗███████╗
╚═╝  ╚═╝╚═╝  ╚═╝╚══════╝╚══════╝
     D R O N E S   I N C .
```

**Engineering autonomous systems for next-generation counter-UAS and kinetic intercept.**

<br>

[![Website](https://img.shields.io/badge/Web-kazedronesnd.com-111827?style=for-the-badge&logoColor=white)](https://kazedronesnd.com)&nbsp;&nbsp;[![Email](https://img.shields.io/badge/Contact-engineering@kazedronesnd.com-111827?style=for-the-badge&logoColor=white)](mailto:engineering@kazedronesnd.com)

<br>

</div>

---

## What We Build

KAZE Drones develops attack-class UAS and loitering munition platforms engineered for counter-UAS and kinetic intercept missions. We own the full stack — RF detection, computer vision, flight control, mission execution, and ground station — built for performance in contested environments.

<br>

## Core Systems

<table>
<tr>
<td width="50%">

### Interceptor
Attack-class UAS airframe with MAVLink/ArduPilot flight control, H.264 video downlink, and autonomous intercept mission profiles.

### KAZE-VISION
Real-time onboard vision pipeline — inference at the edge, tuned for aerial target detection and classification in low-latency, high-stakes scenarios.

### SPECTRA
Passive RF-based counter-UAS using software-defined radio. Detects drones and operators from their RF signature without active emission.

</td>
<td width="50%">

### KAZE-LINK
Encrypted telemetry and command link layer. Designed for resilience in RF-contested environments.

### DRONE-DETECTION-MODEL
Custom YOLO-based detection models trained on curated aerial datasets. Purpose-built for drone-vs-background classification.

### Log Viewer
Post-flight analysis platform — 3D mission replay via Cesium, KCFS ingest, curated analyses, and PDF reporting.

</td>
</tr>
</table>

<br>

## Technology Stack

```
┌─────────────────────────────────────────────────────────────────┐
│                      KAZE FULL STACK                            │
├───────────────┬───────────────┬───────────────┬─────────────────┤
│   DETECT      │   DECIDE      │   ENGAGE      │   REVIEW        │
│               │               │               │                 │
│  SPECTRA SDR  │  YOLO Vision  │  MAVLink FC   │  Log Viewer     │
│  RF Analysis  │  Edge Infer   │  Autopilot    │  3D Replay      │
│  Signal Proc  │  Target Class │  GCS Bridge   │  Flight Review  │
└───────────────┴───────────────┴───────────────┴─────────────────┘
```

<br>

## Engineering Principles

- **Edge-first** — inference and control run onboard; ground dependency is minimized
- **Full-stack ownership** — from raw RF signals to mission execution, we build what we fly
- **Data-driven** — every flight informs the next; detection models are continuously refined
- **Contested-environment ready** — designed for degraded comms, GPS-denied, and ECM scenarios

<br>

---

<div align="center">

**KAZE Drones Inc.** &nbsp;·&nbsp; United States &nbsp;·&nbsp; [kazedronesnd.com](https://kazedronesnd.com)

*All development repositories are private and access-controlled.*

</div>
