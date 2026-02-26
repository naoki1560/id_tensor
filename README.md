# ID Theory: Molecular Deviation Tensor

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![DOI](https://img.shields.io/badge/DOI-10.5281/zenodo.18223828-blue)

[ORCID: 0009-0002-0823-6109](https://orcid.org/0009-0002-0823-6109)
* **[`id_tensor.py`](id_tensor.py)**
* **[`PAPER.md`](PAPER.md)**


# 原子特性の幾何学的解釈と結合角の解析
# Geometric Interpretation of Atomic Periodicity and Bond Angle Analysis

## 概要 / Concept

### (JP)
本プロジェクトは、従来の周期表という平面的な枠組みを、エネルギー（s性）を標高とした3次元の**「ポテンシャル曲面」**として再定義します。この幾何学的な視点により、元素の性質を以下の三要素で解釈します。

* **形状：深淵へと向かう「ポテンシャル・ファンネル」**
  窒素(N)や酸素(O)などの第2周期元素を「高エネルギーの縁（リム）」に配置し、そこからエネルギーが緩和していく立体的なくぼみを想定します。

* **測地線と等高線**
  * **族（縦の列）：** 頂上から底へと向かう「測地線（最短ルート）」。
  * **周期（横の列）：** 同じエネルギーレベルを示す「等高線」。

* **90°の幾何学的特異点**
  第5・第6周期の重原子が到達する、軌道混成を失った状態を「すり鉢の底」として定義します。ここでは分子は宇宙の基本座標系である「純粋な直交空間（90°）」へと収束します。

### (EN)
This project redefines the traditional 2D periodic table as a 3D **"Potential Surface (Manifold)"** where energy levels (s-character) are treated as elevation. This geometric perspective interprets elemental properties through three key elements:

* **Shape: The "Potential Funnel" Toward the Abyss**
  Elements from Period 2 (such as N and O) are positioned at the "High-Energy Rim," descending into a 3D potential well where informational and energetic deviation is relaxed.

* **Geodesics and Contours**
  * **Groups (Vertical):** Defined as **"Geodesics"**—the paths of least resistance from the rim to the center.
  * **Periods (Horizontal):** Defined as **"Contours"**—equipotential lines representing specific energy thresholds.

* **The 90° Geometric Singularity**
  The basin of the funnel represents the state reached by heavy atoms in Periods 5 and 6. At this stability point, hybridization is lost, and the molecular structure converges into a **"Pure Orthogonal Space (90°)"** synchronized with the universe's fundamental Cartesian coordinate system.

---

## 目的 / Objectives

### (JP)
1. **幾何学的配置からの結合角算出：** 統計的手法を用いて、原子の幾何学的性質から決定論的に結合角を導き出します。
2. **逆計算による特性解析：** 得られた結合角から、未知の分子構造や化学的特性の解析に繋げます。
3. **誤差の吸収：** 従来の計算手法では「ノイズ」とされていた微細な数値の揺らぎを、空間の局所的な曲率として解釈し、極めて高い精度での幾何学的プロジェクションを達成します。

### (EN)
1. **Deterministic Bond Angle Calculation:** Using statistical and geometric methods to derive bond angles directly from atomic properties.
2. **Inverse Structural Analysis:** Utilizing derived angles to analyze unknown molecular structures and chemical characteristics.
3. **Absorption of Deviations:** Minute numerical fluctuations, traditionally treated as "noise," are interpreted as local spatial curvatures, achieving high-precision geometric projection.

---

## 物理モデルの基幹 / Core Physical Model

### (JP)
本アルゴリズムは、以下の幾何学的レンズを用いて結合角度（$\theta$）を算出します。

$$\cos \theta = \frac{S}{S - 1}$$

ここで、$S$ は系全体の混成状態（標高）を示し、システムが緩和して底（$S \to 0$）に近づくほど、角度は幾何学的必然として90°へ収束します。

### (EN)
The algorithm calculates the bond angle ($\theta$) through the following geometric lens:

$$\cos \theta = \frac{S}{S - 1}$$

Where $S$ represents the hybridization state (elevation) of the system. As the system relaxes toward the basin ($S \to 0$), the angle geometrically and inevitably converges to 90°.

---

## AIの利用について / Use of AI

### (JP)
本プロジェクトの核となる理論および幾何学的解釈は、人間（著者）独自の洞察によるものです。AIは、データの統計処理、計算の自動化、およびプログラムコードの最適化のための補助ツールとして活用されています。

### (EN)
The core theory and geometric interpretations of this project are based on the original insights of the human author. AI is utilized as a supplementary tool for statistical data processing, computational automation, and program code optimization.
