# ID Theory: Molecular Deviation Tensor

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.18223828-blue)

[ORCID: 0009-0002-0823-6109](https://orcid.org/0009-0002-0823-6109)
* **[`id_tensor.py`](id_tensor.py)**
* **[`PAPER.md`](PAPER.md)**

🌌 ID Tensor
A 10-Dimensional Geometric Engine for Molecular Bond Angles
👁️ The Vision: Understanding Intrinsic Geometric Structures
The ID Tensor project breaks away from the conventional approach of treating molecular bond angles as a mere patchwork of individual chemical properties or statistical approximations of quantum chemical calculations.
Instead, we focus on the intrinsic geometric structure (a manifold) hidden behind fundamental macroscopic physical quantities: Electronegativity (EN), Ionization Energy (IE), and Atomic Radius (R). Atoms do not bond randomly; they follow the spatial distortions woven by these physical quantities and are geometrically locked into specific angles (converging toward a state of Omega). This is the core design philosophy of this engine.
⚙️ The Breakthrough: From Statistical Approximation to "Geometric Solutions"
Traditional machine learning and data science approaches merely derive statistical trends (curve fitting) from massive datasets.
ID Tensor maps the three input variables (EN, IE, R) into a 10-dimensional tensor space (incorporating squared and cross terms). By passing through this 10D space, the engine geometrically absorbs the complex spatial distortions caused by inner-shell electrons (such as d and f orbitals). As a result, rather than relying on ambiguous statistical guessing, it successfully derives deterministic "geometric solutions" (perfect bond angle predictions) that eliminate errors to the absolute mathematical limit.
🔄 The Potential: Exploration of the Unknown via "Inverse Design"
The fact that a microscopic result like a bond angle can be perfectly described as a tensor of macroscopic physical quantities means that Inverse Calculation (Inverse Design) becomes possible.
With the rules of this spatial structure (the manifold) visualized, we unlock powerful new approaches:
• Predicting Unknown Data: Accurately deducing the bond angles of heavy elements not included in the training data (e.g., Bismuth) strictly from the tensor's geometric rules.
• Reverse Engineering: When a material with a specific bond angle (spatial structure) is desired, calculating backwards to determine the exact combination of EN, IE, and R required to achieve it.
ID Tensor is not just a script that calculates angles. It is the first compass for decoding geometric structures from data and "reverse engineering" new materials and unknown physical behaviors.

# 1. Initialize the ID Tensor
tensor = ID_Tensor()

# 2. Calibrate using 10D tensor mapping (learning the manifold)
tensor.calibrate()

# 3. Verify the geometric lock (Error should approach 0.0000°)
tensor.verify()

# 4. Predict unknown element strictly from geometric rules
tensor.predict("Bismuth (Bi)", EN=2.02, IE=7.289, R=1.51)
