# QFLCH: Quantum Field Lens Coding Hypercube, Hardware Synthesis Engine and Phase Model  
Technical: [![On GitHub](https://img.shields.io/badge/GitHub-SoftwareImpacts-009688.svg?style=flat&amp;logo=github)](https://github.com/SoftwareImpacts/SIMPAC-2024-159)
[![Mendeley Badge](https://img.shields.io/badge/Mendeley_Data-v.3%2B-%239D1620?logo=mendeley&logoColor=%239D1620
)](https://data.mendeley.com/datasets/gf2s8jkdjf/3)
[![VSCode Badge](https://img.shields.io/badge/Code%20in%20VS%20Code-v.1.3-blue.svg?style=flat&amp;logo=vscode)](https://codeocean.com/capsule/6853712/tree/v2/code/root/lab/sim/QFLCC%20classifiers/QAI-LCode_QFLCC.py)
[![Code in Python v>3.1](https://img.shields.io/badge/Python-v.3+-3776AB.svg?style=flat&amp;logo=python&amp;logoColor=white)](https://codeocean.com/capsule/6853712/tree/v2/code/root/lab/sim/QFLCC%20classifiers/QDF-LCode_IBMQ-2024-codable.py)
[![Jupyter Lab](https://img.shields.io/badge/Jupyter-Lab-F37626.svg?style=flat&amp;logo=Jupyter)](https://codeocean.com/capsule/6853712/tree/v2/code/root/lab/sim/QFLCC%20classifiers/QDF-LCode_IBMQ-2024-raw-codable.ipynb)
[![Open in Code Ocean](https://img.shields.io/badge/CS-Open_in_Code_Ocean-%2329A7DF?logo=codecrafters&logoColor=%2329A7DF
)](https://codeocean.com/capsule/6853712/tree/v2)

Social: [![GitHub Profile](https://img.shields.io/badge/GitHub-phibal12%20profile%20+%20projects-009688.svg?style=flat&amp;logo=github)](https://github.com/phibal12)
[![Author's LinkedIn](https://img.shields.io/badge/LinkedIn-blue.svg?style=flat&amp;logo=linkedin&logoColor=white)](http://ca.linkedin.com/pub/philip-baback-alipour/b/b13/b35)

Academic: [![Author's ORCID](https://img.shields.io/badge/ORCID-0000--0003--1037--018X-A6CE39?logo=orcid)](https://orcid.org/0000-0003-1037-018X)

Math Mode: ![Made with MathJax](https://img.shields.io/badge/Made_with_MathJax-v.4.1.1-009688.svg)<details><summary> Details at [https://www.mathjax.org](https://www.mathjax.org)</summary> <script type="text/javascript" id="MathJax-script" async
  src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
</script>
<script>
  window.MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    }
  };
</script> </details>

Legal: [![CC BY 4.0][cc-by-shield]][cc-by]
<hr/>

This repository contains the code for the QFLCS (Quantum Field Lens Coding Simulator) as part of its algorithm, QFLCA (Quantum Field Lens Coding Algorithm) project.
The project repositories are available at https://data.mendeley.com/datasets/gf2s8jkdjf/3 and https://doi.org/10.24433/CO.9905505.v2, which include the code, project website documentation, and demo video files.

# QF-LCD: Quantum Field Lens Coding Dashboard
## QF-LC Hypercube, Quantum Hardware Synthesis Engine & Phase Simulator 

![Version](https://img.shields.io/badge/Version-1.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Web%20(HTML5/JS)-success.svg)
![Field](https://img.shields.io/badge/Field-Quantum%20Computing%20%7C%20Logic%20Synthesis-purple.svg)

## Overview
The **Quantum Field Lens Coding Algorithm (QF-LCA) Synthesis Engine** is an interactive, browser-based simulation dashboard bridging theoretical quantum physics with applied hardware engineering. It translates theoretical quantum field physics into practical, thermodynamically-aware digital logic and quantum circuit synthesis.

By utilizing the QF-LCA model, this engine bypasses the visual and computational intractability of traditional Karnaugh Maps (K-maps). It leverages non-local entanglement bonds across *N*-dimensional space to perform global logic reduction—scaling seamlessly from simple 2D arrays up to massive 12D network topologies.

## Live Widget
👉 **[Launch the QF-LCA Synthesis Engine Live](#)** *(Replace with your GitHub Pages link)*

## Key Features

### 1. *N*-Dimensional Logic Synthesis & Intractability Bypassing
* **Scalability:** Process logic arrays from basic 2-variable systems up to 12-variable (4096 nodes) networks.
* **Intractability Validation:** Includes explicit hardware failure-testing presets (e.g., 6D, 7D, and 12D Costly Entanglement vs. Deterministic configurations).
* **Global Field Evaluation:** Replaces sequential $d_H=1$ adjacency mapping with global, multi-dimensional correlations, collapsing massive sub-cubes instantaneously based on entanglement parameters.

### 2. Thermodynamic Phase Simulation (Eq. 53 Integration)
* **Real-time Physics:** Tune parameters such as Spatial Density ($|\kappa|^2\rho$), Lens Lattice Distance ($L$), and the $\nu$ Factor to observe physical phase shifts.
* **Phase Tracking:** Dynamically transition between the **Superfluid (SF)** phase, the **Quantum Density Fluctuation (QDF)** phase, and the **Target Hit ($d_H$)** probability peak.
* **Thermodynamic Mapping:** Includes a live Entanglement Entropy (EE) vs. Spatial Density curve.

### 3. Dual-Compilation: Classical & Quantum Circuitry
* **FPGA-Ready Classical Logic:** Generates thermodynamically-stable Boolean logic representations and synthesizes them into raw **VHDL** for classical hardware programming.
* **QPU-Ready Quantum Circuits:** Compiles the entanglement loop into raw **OpenQASM 2.0**, ready to be deployed on real quantum processing units (IBM Quantum, Amazon Braket, IonQ).

### 4. Phase-Reactive Hypercube Visualization
* A fully interactive, 3D-projected *N*-dimensional Hypercube.
* Visualize physical wave propagation: Watch free particles orbit, entangle, and form active topological bridges between positional nodes.
* **Wave Collapse Visualization:** Toggle isolated target states to observe absolute classical deterministic wave collapse `(<s>Ψ</s> | bit sequence)`.

### 5. Research & Dataset Generation
* Built-in capabilities to execute simulations and export the precise probabilistic outputs, active node mappings, and terminal logs to `.csv` formats for secondary Quantum AI evaluation.

## Theoretical Background
Traditional digital design assumes ideal logic gates (100% deterministic 1s and 0s) without accounting for ambient thermal limits. The QF-LCA engine applies **Equation 53** (from Ref. [1]) to derive quantum transition probabilities:

$$P(\Phi \to \Psi) = \frac{4(N - 1)^2}{9[N(N - 1)/2]\nu}$$

This ensures that the synthesized logic actively routes around physical phase limits. When ambient noise or spatial mismatch disrupts coherence, the system accurately reflects deterministic fallbacks and leakage, measuring Entanglement Entropy (EE) bounds against physical resource loads.

## Quick Start
This application is entirely client-side with zero external dependencies. 
1. Clone the repository.
2. Open `index.html` in any modern web browser (Chrome, Edge, Firefox, Safari).
3. Select your dimensions, tweak the thermodynamic sliders, and click **"Execute Quantum Synthesis"**.

## References
1. P.B. Alipour, T.A. Gulliver, *Quantum Double-field Model and Application*, SSRN, Elsevier BV (2024), Article 4595442. [DOI: 10.2139/ssrn.4595442](https://dx.doi.org/10.2139/ssrn.4595442)
2. P.B. Alipour, T.A. Gulliver, *Quantum Field Lens Coding and Classification Algorithm to Predict Measurement Outcomes*, MethodsX, Elsevier BV (2023), Article 102136. [DOI: 10.1016/j.mex.2023.102136](https://doi.org/10.1016/j.mex.2023.102136)
3. P.B. Alipour, T.A. Gulliver, *QF-LCA dataset: Quantum Field Lens Coding Algorithm for system state simulation and strong predictions*, Data in Brief, Elsevier BV (2024), Article 110789. [DOI: 10.1016/j.dib.2024.110789](https://doi.org/10.1016/j.dib.2024.110789)
4. P.B. Alipour, T.A. Gulliver, *QF-LCS: Quantum Field Lens Coding Simulator and Game Tool for Strong System State Predictions*, Software Impacts, Elsevier BV (2024), 100703. [DOI: 10.1016/j.simpa.2024.100703](https://doi.org/10.1016/j.simpa.2024.100703)


# QF-LCA Quantum-Hardware Synthesis Engine & Phase Simulator

![Version](https://img.shields.io/badge/Version-1.0-blue.svg)
![Platform](https://img.shields.io/badge/Platform-Web%20(HTML5/JS)-success.svg)
![Field](https://img.shields.io/badge/Field-Quantum%20Computing%20%7C%20Logic%20Synthesis-purple.svg)

## Overview
The **Quantum Field Lens Coding Algorithm (QF-LCA) Synthesis Engine** is an interactive, browser-based simulation dashboard bridging theoretical quantum physics with applied hardware engineering. It translates theoretical quantum field physics into practical, thermodynamically-aware digital logic and quantum circuit synthesis.

By utilizing the QF-LCA model, this engine bypasses the visual and computational intractability of traditional Karnaugh Maps (K-maps). It leverages non-local entanglement bonds across *N*-dimensional space to perform global logic reduction—scaling seamlessly from simple 2D arrays up to massive 12D network topologies.

## Live Widget
👉 **[Launch the QF-LCA Synthesis Engine Live](#)** *(Replace with your GitHub Pages link)*

## Key Features

### 1. *N*-Dimensional Logic Synthesis & Intractability Bypassing
* **Scalability:** Process logic arrays from basic 2-variable systems up to 12-variable (4096 nodes) networks.
* **Intractability Validation:** Includes explicit hardware failure-testing presets (e.g., 6D, 7D, and 12D Costly Entanglement vs. Deterministic configurations).
* **Global Field Evaluation:** Replaces sequential $d_H=1$ adjacency mapping with global, multi-dimensional correlations, collapsing massive sub-cubes instantaneously based on entanglement parameters.

### 2. Thermodynamic Phase Simulation (Eq. 53 Integration)
* **Real-time Physics:** Tune parameters such as Spatial Density ($|\kappa|^2\rho$), Lens Lattice Distance ($L$), and the $\nu$ Factor to observe physical phase shifts.
* **Phase Tracking:** Dynamically transition between the **Superfluid (SF)** phase, the **Quantum Density Fluctuation (QDF)** phase, and the **Target Hit ($d_H$)** probability peak.
* **Thermodynamic Mapping:** Includes a live Entanglement Entropy (EE) vs. Spatial Density curve.

### 3. Dual-Compilation: Classical & Quantum Circuitry
* **FPGA-Ready Classical Logic:** Generates thermodynamically-stable Boolean logic representations and synthesizes them into raw **VHDL** for classical hardware programming.
* **QPU-Ready Quantum Circuits:** Compiles the entanglement loop into raw **OpenQASM 2.0**, ready to be deployed on real quantum processing units (IBM Quantum, Amazon Braket, IonQ).
* **Interactive Tutorial:** Features a side-by-side generated visual schematic and OpenQASM code viewer mapped directly to the active hypercube state.

### 4. Phase-Reactive Hypercube Visualization
* A fully interactive, 3D-projected *N*-dimensional Hypercube.
* Visualize physical wave propagation: Watch free particles orbit, entangle, and form active topological bridges between positional nodes.
* **Wave Collapse Visualization:** Toggle isolated target states to observe absolute classical deterministic wave collapse `(<s>Ψ</s> | bit sequence)`.

### 5. Research & Dataset Generation
* Built-in capabilities to execute simulations and export the precise probabilistic outputs, active node mappings, terminal logs, and compiled circuit diagrams to both raw **.CSV** and offline, fully-styled **.HTM** dataset formats for secondary Quantum AI evaluation.

---

## Theoretical Background

Traditional digital design assumes ideal logic gates (100% deterministic 1s and 0s) without accounting for ambient thermal limits. The QF-LCA engine bridges this gap by applying **Equation 53** (from Ref. [1]) to derive physical quantum transition probabilities:

$$P(\Phi \to \Psi) = \frac{4(N - 1)^2}{9[N(N - 1)/2]\nu}$$

This ensures that the synthesized logic actively routes around physical phase limits. When ambient noise or spatial mismatch disrupts coherence, the system accurately reflects deterministic fallbacks and leakage, measuring Entanglement Entropy (EE) bounds against physical resource loads.

### Revealing Hidden Bell States via QDF Lensing

In standard environments, thermal noise and ambient spatial density mask distant correlations ($d_H \ge 1$). To reveal hidden Bell states (|00⟩, |01⟩, |10⟩, |11⟩) without destroying superposition, the QF-LCA employs **Quantum Double-Field (QDF) Lensing**.

By introducing an intercepting field—an **Ancilla (Eve)**—the system breaks parity between the superposing field (Alice) and the ground state trap (Bob). Eve acts as a parity-breaking "lens", absorbing complex phase interactions to stabilize the orbital swarm and project the hidden correlation into a measurable localized state.

#### The QDF Lens Circuit Architecture

```text
       ENTANGLEMENT         QDF TRANSFORMATION          REVEALED 
          SOURCE              (THE LENS)                 STATE
          
q0 ────[ H ]────●─────────────────────────────[ M ]──> bit 0
                │               ┌───────┐      
                │               │       │      
q1 ────────────[ X ]───────●────┤  QDF  ├─────[ M ]──> bit 1
                           │    │       │
             (Entangled    │    │ LENS  │      (Hidden bits 
                Pair)      │    │       │       recovered)
                           │    │       │
ancilla  ───────────────[ X ]───┤       ├─────[ M ]──> Eve's Field 
(Eve)                           └───────┘              Signature


```

#### Doubling the P vs. Information Density Increase

On an event-by-event basis, "information density" is refer to self-information (or surprisal), which is 
-log(p). Events with lower probability have higher information density because they provide more "surprise" or new information when they occur. 
This transformation ($\kappa\Phi \to \Psi$) however, allows the observer to bypass standard one-shot measurement limitations via $n-2$ state elimination. Through this selective measurement, the system distinguishes between all four Bell states with a higher probability $P \ge 2/3$ according to Eq. (53). 

This probability $P$ is measured at $\langle M \rangle$, which represents the adder Hamiltonian from the publication, where after measurement the final physical count is revealed or Decoherence safely occurs (from Ref. [2]).


## Author & Contact
**Dr. Philip B. Alipour** *Quantum Architect & Hardware Engineering Researcher* For bug fixes, updates, or collaboration inquiries, please reach out via:
* [philipbaback_orbsix@msn.com](mailto:philipbaback_orbsix@msn.com)
* [philipbaback66@gmail.com](mailto:philipbaback66@gmail.com)

&copy; Copyright 2026, Philip B. Alipour. All Rights Reserved.


[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg
