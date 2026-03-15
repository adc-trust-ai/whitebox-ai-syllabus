# Whitebox AI Syllabus 🎓
**The Expert-Curated Path to Mastering Interpretable Machine Learning**

[![BarcelonaTech](https://img.shields.io/badge/Faculty-BarcelonaTech%20(UPC)-blue)](https://www.upc.edu)
[![UPF Economics](https://img.shields.io/badge/Faculty-Pompeu%20Fabra%20(UPF)-red)](https://www.upf.edu)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

## 📌 Syllabus
* [Level 0: The Vision: Why Whitebox?](#-level-0-the-vision)
* [Level 1: Math & Python Foundations](#-level-1-math-and-python-foundations) ![Status: Live](https://img.shields.io/badge/Status-Live-green)
* [Level 2: White-Box Literature](#-level-2-white-box-literature) ![Status: Curating](https://img.shields.io/badge/Status-Curating-orange)
* [Level 3: TRUST™: A Framework for Trustworthy AI](#-level-3-trust-a-framework-for-trustworthy-ai) ![Status: Planned](https://img.shields.io/badge/Status-Planned-red)
* [How to Contribute to the Repository](#-how-to-contribute-to-the-repository)
* [Complementary Resources](#-complementary-resources)

---

## 💡 Level 0: The Vision
### The End of the Black-Box Era in Tabular ML
For decades, large sectors of academia and industry have been lulled into a false sense of security by high-performance "Black-Box" models for tabular data that prioritize predictive power over human comprehension. In the era of the EU AI Act and the rise of high-stakes, AI-informed decision-making, a model you cannot explain is no longer an asset no matter how accurate -- it is a liability. What you cannot see you cannot audit, and what you cannot audit you cannot fix (e.g. biases or logic failures).

This syllabus is the "White-Box" antidote, which shows that a safer, more human-centric AI future is possible. It is the exact self-learning stack I recommend to my most ambitious students at Barcelona Tech and Pompeu Fabra.

The truth is that not all academics-practitioners agree with the brute-force approach to forecasting that is currently mainstream. Join the "Whitebox Resistance" today!🛡

### A Note on the Journey
Mastering every resource in this repository would be an Herculean task and likely unnecessary for most. However, the sequence presented forms a logical progression from raw intuition to mathematical rigor. You are encouraged to critically pick and choose.

### 🧭 How to Navigate the Syllabus
Choose your depth based on your current objective:

* **The ML Tourist (L1 Lite):** Watch the **3Blue1Brown** Linear Algebra and Calculus playlists. Perfect for building the visual intuition required to discuss ML at a high level without the heavy lifting.
* **The Rigorous Practitioner (L1):** Master the math foundations and the **Python** module. This is the baseline for anyone looking to build (or at least responsibly use) ML models.
* **The Academic (L1 + L2):** For those that want to truly understand foundational research work on white-box ML.
* **The Auditor (L1 + L3):** Learn the math foundations and the frameworks of inherently interpretable ML. Designed for model auditors or those who must justify model decisions to regulators or stakeholders.
* **The Architect (L1 + L2 + L3):** The full stack. For those intending to expertly use or even develop their own intrinsically interpretable frameworks at the bleeding edge of the research frontier.

---

## ✅ Level 1: Math and Python Foundations
*Master the 20% of math & programming that puts you ahead of the 80% of practitioners.*

### 🔢 Linear Algebra
| Resource | Why it's here |
| :--- | :--- |
| [**Essence of LinAlg (3B1B)**](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | Essential visual intuition to "see" what matrices are actually doing. |
| [**MIT 18.06 (Strang, MIT)**](https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8) | The gold standard. Focus on the Four Fundamental Subspaces to understand the geometry of data.|
| [**Algebra (Censor, Technion)**](https://www.youtube.com/playlist?list=PLW3u28VuDAHJNrf3JCgT0GG_rjFVz0-j9)| Academic rigor at its finest. This is where you learn to treat matrices not just as grids of numbers, but as linear operators.|


### 📈 Calculus & Optimization
| Resource | Why it's here |
| :--- | :--- |
| [**Essence of Calculus (3B1B)**](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) | A good visual introduction to different calculus topics.
| [**Calculus One (Fowler, Ohio State)**](https://www.youtube.com/playlist?list=PLaLOVNqqD-2H1OJRzQDqYjGjM-XeJCALw) | Unrivaled conceptual clarity. If you want to understand how a model 'learns' via gradients without getting lost in the notation, start here.|
| [**Calculus Two (Fowler, Ohio State)**](https://www.youtube.com/playlist?list=PLaLOVNqqD-2GXdakC-Sl2qJ0vl6g0lawb) | A beginner-friendly deep dive into sequences and series. |
| [**Calculus 1 (Censor, Technion)**](https://www.youtube.com/playlist?list=PLW3u28VuDAHJymExTBCNnaI6TymzRGsUV) | For those looking to take their calculus rigor to the next level. |
| [**Calculus 2 (Censor, Technion)**](https://www.youtube.com/playlist?list=PLW3u28VuDAHLWNxKyfoBQSVBp-fhWrDr0) | A rigorous yet beginner-friendly coverage of Multivariate calculus. |


### 🎲 Probability and Statistics
| Resource | Why it's here |
| :--- | :--- |
| [**Probability Bootcamp (Brunton, UW)**](https://www.youtube.com/playlist?list=PLMrJAkhIeNNR3sNYvfgiKgcStwuPSts9V) | Good and varied selection of introductory-to-intermediate Probability topics. |
| [**Statistics Fundamentals (StatQuest)**](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9) | Intuitive visuals and coverage of most fundamental topics. |
| [**Statistics (Organic Chem Tutor)**](https://www.youtube.com/playlist?list=PL0o_zxa4K1BVsziIRdfv4Hl4UIqDZhXWV) | Good and varied selection of introductory-to-intermediate Statistics topics. |
| [**Econometrics 1 (Ben Lambert)**](https://www.youtube.com/playlist?list=PLwJRxp3blEvZyQBTTOMFRP_TDaSdly3gU) | A fantastic Khan-Academy-style introduction to Econometrics and Time Series. |
| [**Econometrics 2 (Ben Lambert)**](https://www.youtube.com/playlist?list=PLwJRxp3blEvb7P-7po9AxuBwquPv75LjU) | Part 2. |


### 🐍 Python
| Resource | Why it's here |
| :--- | :--- |
| [**Python 0 (Visually Explained)**](https://www.youtube.com/playlist?list=PL8HmoRTjTSlEgS2GsFaDr9zDLC1xD9FZf) | A friendly introduction to select Python topics including Google Colab notebooks. |
| [**Python 1 (Corey Schafer)**](https://www.youtube.com/playlist?list=PL-osiE80TeTt2d9bfVyTiXJA-UTHn6WwU) | Perhaps the no. 1 recommended playlist to learn Python. |
| [**Python 2 (Corey Schafer)**](https://www.youtube.com/playlist?list=PL-osiE80TeTsqhIuOqKhwlXsIBIdSeYtc) | The sequel: Object Oriented Programming principles. |


### 🤖 Machine Learning
| Resource | Why it's here |
| :--- | :--- |
| [**Machine Learning (Ng, Stanford)**](https://www.youtube.com/playlist?list=PLiPvV5TNogxIS4bHQVW4pMkj4CHA8COdX) | THE original introductory ML playlist -- still worth it despite its low video resolution by today's standards. |
| [**Statistical Learning (StatQuest)**](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF) | A gentle and visual introduction to most of the core topics in classical statistical learning. |
| [**Machine Learning I (GaTech)**](https://www.youtube.com/playlist?list=PLAwxTw4SYaPl0N6-e1GvyLp5-MUMUjOKo) | A friendly playlist focused on supervised learning. |
| [**Machine Learning II (Ng, Stanford)**](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU) | Suitable for advanced undergraduates or junior graduate students in ML. |
| [**Learning from Data (Mostafa, Caltech)**](https://www.youtube.com/playlist?list=PLnIDYuXHkit4LcWjDe0EwlE57WiGlBs08) | A rigorous introduction to Learning Theory. |


---

## ⌛ Level 2: White-Box Literature
![Status: Curating](https://img.shields.io/badge/Status-Curating-orange)

*Content currently being selected. This section will cover the transition from Black-Box ensembles to inherently interpretable architectures, visitng XAI tools along the way as an occasionally useful middle-ground or complementary approach.*

> **Sneak Peek:** We will be covering the seminal works of the world leading White-box AI Schools of Thought: Stanford (Friedman, Hastie, Tibshirani), Wisconsin-Madison (Loh, Zhang, Sankaran), Duke (Rudin, Semenova), UC Berkeley (Breiman), and more.

---

## ⏳ Level 3: TRUST™: A Framework for Trustworthy AI
![Status: Planned](https://img.shields.io/badge/Status-Planned-red)

*The final frontier: Scaling theory into a production-grade framework for high-stakes healthcare, banking and regulatory compliance.*

> **Sneak Peek:** The framework is implemented in the [trust-free](https://github.com/adc-trust-ai/trust-free) Python package.
---

## 🤝 How to Contribute to the Repository
The **Whitebox AI Syllabus** is a living curriculum. While the core sequence is curated to maintain academic rigor, contributions from the community are always welcome.

### How you can help:
* **Suggest a "Gold Standard" Resource:** If you know a playlist or open-access paper that explains a complex concept with exceptional clarity, please open an Issue.
* **Report Broken Links:** Help keep the library functional for everyone.

### The Curation Standard
To maintain the "Syllabus" quality, all suggestions will be vetted against three criteria:
1. **Conceptual Clarity:** Does it simplify the complex without losing the essence?
2. **Foundational Strength:** Does it contribute to a "White-box" understanding of ML?
3. **Open Access:** Only free-to-access resources are accepted. 

> **Note to Authors:** If you have developed a high-quality educational resource or research work that aligns with our vision, feel free to open an Issue or otherwise reach out. Resources that naturally blend in with the Syllabus will be added there, while synergistic resources will be added under Complementary Resources.

---

## 📚 Complementary Resources:
* **[Carl McBride Ellis's Compendium](https://github.com/Carl-McBride-Ellis/Compendium-of-free-ML-reading-resources):** An extensive, multi-topic library of free ML reading.

---

### 👤 About the Author
Albert Dorador, Ph.D. is a researcher and Adjunct Professor of Mathematics and Computational Statistics focused on statistical learning and high-stakes AI transparency. He currently teaches at BarcelonaTech (UPC) within the Bachelor of Artificial Intelligence and at Pompeu Fabra (UPF) in the Bachelor of Economics. He holds a Ph.D. in Statistics from UW-Madison (la Caixa Fellow) and is the developer of the TRUST™ machine learning framework, including the Renet™ and AdaLogit™ models, the high-performance Ridge-OLS TurboSolve™, and model-agnostic feature importance deterministic estimators ("One permutation is all you need"). The TRUST™ framework has been successfully applied both in regulated financial sectors and in humanitarian efforts, such as in his collaboration with the Mundo Orenda NGO to assist clinicians in Angola with malnourished children's recovery forecasting.

*Disclaimer: This repository is a personal educational initiative and does not represent the official curriculum or views of UPC or UPF.*
