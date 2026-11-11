# ScaleRoad OS — Design Laboratory Preview (Temporary Showcase)

> **Live Interactive Preview**: [https://superzosar.github.io/scaleroad-ux-preview/](https://superzosar.github.io/scaleroad-ux-preview/)
> 
> *Temporary showcase branch for stakeholder review. Will be taken down after evaluation.*

---

## Overview

**ScaleRoad OS** is an agent-native operating system tailored for Egyptian residential finishing studios and site operators. This preview demonstrates the modern, architecturally styled interface foundation built on **shadcn/ui (Luma style)** with **Base UI**, **Tailwind CSS**, and **Remix Icons**.

---

## Key Features in this Preview

### 1. Clients & Studio Executive Overview Dashboard
- **CAD Coordinate Watermark**: Technical metadata (`GRID: CAI-26`, `DATUM: +0.00m`, `SPEC: ECP-203`).
- **Studio Telemetry KPI Grid**: Committed Portfolio (`EGP 15.40M`), Supervised Area (`1,445 m²`), Engineering Tolerance Index (`97.4%`), and Field Sign-off Velocity.
- **Finishing Trades Burndown Chart**: Progress across core Egyptian finishing disciplines (MEP Rough-in, Laser Screed, Ceilings, Carrara Marble, Joinery, Finishing Paint).
- **Radial Completion Gauge**: Overall progress (`48.2%`) with compound breakdown (Palm Hills, Badya, El Patio, Katameya, Mivida).
- **Client Accounts Master Table**: Financial commitments, progress bars, tolerance status, and supervising engineer in charge.

### 2. Projects Portfolio Register
- Quick portfolio pulse (`05` Total, `01` Action required, `01` On site, `01` Intake draft).
- Segmented status filters (`All`, `Needs review`, `In progress`, `Intake`) and live search.
- Interactive routing: Click on any project or action to inspect site details.

### 3. Villa 104 Site Review & Interactive Blueprint Spatial Control
- **Interactive Architectural Floorplan**: Vector blueprint CAD sheet with room bounding boxes and engineering pins.
- **Bi-directional Focus**: Clicking rooms (`Living`, `Kitchen`, `Primary Suite`, `Terrace`) filters observations; clicking observations focuses the room.
- **Engineering Observations Ledger**: Egyptian Building Code ECP-203 tolerance checks (`±2mm`), laser measurements, and status approvals.
- **High-Resolution Site Photographs**: Timestamped, verified site intake imagery.
- **Live Audit Stream**: Real-time sign-offs and attribution.

### 4. Dynamic Typography Switcher (13 Typefaces / 6 Presets)
Switch typography instantly across the entire application with zero reload:
- 📐 **Architectural Studio** *(Default)*: `Raleway Variable` + `IBM Plex Sans Arabic`
- 🛸 **Engineering CAD**: `Space Grotesk` + `Alexandria`
- ⚡ **Product UI (Linear)**: `Plus Jakarta Sans` + `Noto Sans Arabic`
- 🇪🇬 **Cairo Atelier**: `Outfit` + `Cairo`
- 📟 **CAD Telemetry**: `JetBrains Mono` + `Alexandria`
- 🏛️ **Luxury Monograph**: `Cormorant Garamond` + `Cairo`

### 5. Multi-Mode Appearance & Direction
- **Light / Dark / System** appearance switching.
- **English LTR / Arabic RTL** full bidirectional layout mirroring with **IBM Plex Sans Arabic** / **Cairo**.
- Deep linkable state via URL query parameters (`?view=overview`, `?font=engineering`, `?theme=dark`, `?lang=ar`).

---

## Quick Navigation Links

- [Live App (Dark Mode)](https://superzosar.github.io/scaleroad-ux-preview/?theme=dark)
- [Live App (Light Mode)](https://superzosar.github.io/scaleroad-ux-preview/?theme=light)
- [Live App (Arabic RTL)](https://superzosar.github.io/scaleroad-ux-preview/?theme=dark&lang=ar)
- [Villa 104 Blueprint Workspace](https://superzosar.github.io/scaleroad-ux-preview/?view=review&theme=dark)
- [Engineering CAD Typography Preset](https://superzosar.github.io/scaleroad-ux-preview/?font=engineering&theme=dark)

---

## Teardown Instructions

To remove this temporary showcase repository when review is complete:

```bash
gh repo delete superzosar/scaleroad-ux-preview --yes
```
