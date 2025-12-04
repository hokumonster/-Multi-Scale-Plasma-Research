# Multi-Scale Plasma & Electromagnetic Physics Research

> Unified research platform investigating electromagnetic and plasma phenomena across 20+ orders of magnitude in scale: from molecular cloud turbulence to galactic dynamos to the cosmic web.

## 📊 Research Programs

### 🌞 Heliophysics & Interstellar Objects (Active: Q4 2024 - Q2 2025)
- **[iso-plasma-analysis](https://github.com/multi-scale-plasma-research/iso-plasma-analysis)** - SPDF data + GPU diagnostics
- **[athena-comet-mhd](https://github.com/multi-scale-plasma-research/athena-comet-mhd)** - MHD simulations
- **[dscovr-data-pipeline](https://github.com/multi-scale-plasma-research/dscovr-data-pipeline)** - NOAA integration

**Status:** 🔄 In progress - Downloading SPDF data, developing CuPy diagnostics, building Athena++ simulations

### 🌍 Magnetospheric Physics (Planned: Q2 2025 - Q4 2025)
- Global MHD modeling
- Substorm dynamics
- Exoplanet habitability

### ⭐ Star Formation & Molecular Clouds (Planned: Q4 2025+)
- Turbulent EM cascades
- Magnetic reconnection
- Protoplanetary disks

### 🌌 Galactic Dynamics & Cosmic Rays (Planned: Q1 2026+)
- Dynamo simulations
- Cosmic ray transport
- Supernova remnants

### 🕸️ Cosmic Web & Large-Scale Structure (Planned: Q2 2026+)
- Cosmological MHD
- Relativistic jets
- AGN feedback

---

## 🛠️ Shared Infrastructure

All programs leverage:
- **GPU Computing**: CuPy, Numba, CUDA (RTX 3090 Ti optimized)
- **MHD Codes**: Athena++, GAMER, ENZO, FLASH
- **Data**: SPDF pipelines, NOAA integrations, custom downloaders
- **Workflow**: Jupyter, Git, GitHub Actions, Zenodo

---

## 📚 Core Repositories

| Repository | Purpose | Status |
|------------|---------|--------|
| [iso-plasma-analysis](https://github.com/multi-scale-plasma-research/iso-plasma-analysis) | SPDF + GPU diagnostics | 🔄 Active |
| [athena-comet-mhd](https://github.com/multi-scale-plasma-research/athena-comet-mhd) | MHD simulations | 🔄 Active |
| [gpu-infrastructure](https://github.com/multi-scale-plasma-research/gpu-infrastructure) | Docker, Conda, CI/CD | ⏳ Planned |
| [research-data](https://github.com/multi-scale-plasma-research/research-data) | Data management | ⏳ Planned |
| [multi-scale-publications](https://github.com/multi-scale-plasma-research/multi-scale-publications) | Papers & preprints | ⏳ Planned |

---

## 🎯 Current Focus: Heliophysics

Analyzing electromagnetic and plasma phenomena around **interstellar objects and comets** using:

1. **Real-time data**: ACE, Wind, DSCOVR (L1 solar wind monitors)
2. **GPU diagnostics**: 100+ derived plasma parameters (Alfvén speed, β, gyroradius, etc.)
3. **Full MHD**: 3D simulations of comet-solar wind interactions
4. **Anomaly detection**: Identifying electromagnetic signatures

### 19 Comet Observation Windows (May 2024 - Jan 2025)
- ATLAS 2019Y4, NEOWISE, Oumuamua, Elenin, ISON, Lovejoy, Leonard, McNaught, Machholz + others
- Baseline + observation windows for each comet
- Complete SPDF coverage (ACE + Wind + DSCOVR)

---

## 🚀 Quick Start (Active Projects)

### For Heliophysics/Comet Analysis:
