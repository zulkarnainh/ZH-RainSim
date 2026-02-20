# ZH-RainSim: A Tool for GCM Rainfall Downscaling

![License](https://img.shields.io/badge/license-Academic_Research_Only-blue.svg)
![Release](https://img.shields.io/badge/release-v1.1.0-green.svg)

**ZH-RainSim** is a standalone desktop tool for downscaling Global Climate Model (GCM) rainfall data.  
It generates future rainfall ensembles using a Markov Chain occurrence model coupled with a Gamma distribution for intensity, supporting hydrological and hydraulic impact assessments under CMIP6 climate scenarios.

---

## Download & Installation

The software, user manual, and sample datasets are available in the **Releases** section.

### 👉 [Download the Latest Version (v1.1.0)]([https://github.com/zulkarnainh/ZH-RainSim/releases](https://github.com/zulkarnainh/ZH-RainSim/releases/tag/ZH-RainSim_v1.1.0))

1. Download `ZH-RainSim_v1.zip` from the link above.  
2. Right‑click the ZIP file → **Extract All…**  
3. Open the extracted folder.  
4. Double‑click **ZH-RainSim_v1.exe**.

> **No installation required — this is a portable application.**

---

## What’s New in v1.1.0

### **1. New Model Validation Module**

- **Baseline Simulation**  
  Automatically runs using historical dates with Change Factors locked at 1.0.

- **Comparative Plotting**  
  Direct visual comparison between observed rainfall and simulated baseline.

- **New Validation Graphs**  
  - Validation Histograms  
  - Average Monthly Trends  
  - Annual Total Rainfall  

---

### **2. Redesigned Results Interface**

| Workflow | Purpose |
|---------|---------|
| **Validation** | Demonstrate model performance using historical datasets |
| **Projections** | Visualize GCM‑driven future climate scenarios |
| **Analysis** | Inspect Change Factors, Markov Transition Probabilities, and other parameters |

---

### **3. Expanded Data Export Capabilities**

A new output file is automatically generated:

- `Validation_Historical_Ensembles.csv`

This enables seamless import into Excel, MATLAB, Python, or OriginLab.

---

### **4. Stability Improvements & Bug Fixes**

- Improved GUI error handling with diagnostic warnings  
- Updated deprecated Pandas `'Y'` offset to `'YE'`  
- Transitioned to a **Folder Build** for faster launch and better antivirus compatibility  

---

## Key Features

- Automated downscaling of CMIP6 GCM rainfall data  
- Stochastic simulation using Markov Chain + Gamma distribution  
- User‑friendly GUI  
- Built‑in visualization tools  
- New validation tools (v1.1.0)  
- Improved export pipeline (v1.1.0)  

---

## License

**Copyright:**  
MyIPO (Reference: LY2026P00740)

- **Academic Research:** Free with citation  
- **Funded Research Projects:** Requires a license  
- **Commercial Use:** Not permitted  

---

## Contact & Support

**Developer:** Zulkarnain Hassan  
**Email:** zulkarnainh@unimap.edu.my  
**Website:** http://zulkarnainh.unimap.edu.my  
**Institution:** Universiti Malaysia Perlis  

---

## Citation

If you use ZH‑RainSim in your research, please cite:

```bibtex
@software{zh_rainsim_2026,
  author       = {Zulkarnain Hassan},
  title        = {ZH-RainSim: A Tool for GCM Rainfall Downscaling},
  year         = {2026},
  publisher    = {GitHub},
  journal      = {GitHub repository},
  howpublished = {https://github.com/zulkarnainh/ZH-RainSim}
}
