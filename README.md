# Whitebox AI Syllabus 🎓
**The Expert-Curated Path to Mastering Interpretable Machine Learning**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

## 📌 Table of Contents
* [Level 0: The Vision: Why Whitebox?](#level-0)
* [Level 1: Math Foundations](#level-1) ![Status: Live](https://img.shields.io/badge/Status-Live-green)
* [Level 2: White-Box Literature](#level-2) ![Status: Curating](https://img.shields.io/badge/Status-Curating-orange)
* [Level 3: TRUST™ Architecture](#level-3) ![Status: Planned](https://img.shields.io/badge/Status-Planned-red)
* [How to Contribute](#contributing)

---

## 💡 Level 0: The Vision
### The End of the Black-Box Era
For decades, both academia and industry have been lulled into a false sense of security by high-performance ensemble models that prioritize predictive power over human comprehension. In the era of the EU AI Act and the rise of high-stakes, AI-informed decision-making, a model you cannot explain is no longer an asset -- it is a liability.
This syllabus is the "White-Box" antidote. It is the exact self-learning stack I recommend to my most ambitious students at Barcelona Tech (Bachelor of Artificial Intelligence) and Pompeu Fabra (Bachelor of Economics).

### A Note on the Journey
Mastering every video in this repository would be an Herculean task and likely overkill for most. However, the sequence presented forms a logical progression from raw intuition to mathematical rigor. You are encouraged to critically pick and choose

---

## ✅ Level 1: Math Foundations
*Master the 20% of math that puts you above the 80% of practitioners.*

### 📐 Linear Algebra (The Skeletal System)
| Resource | Why it's here |
| :--- | :--- |
| [**Essence of LinAlg (3B1B)**](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | Essential visual intuition to "see" what matrices are actually doing. |
| **[MIT 18.06 (Strang, MIT)**](https://www.youtube.com/playlist?list=PLE7DDD91010BC51F8) | The gold standard. Focus on the Four Fundamental Subspaces to understand the geometry of data.|
| [**Algebra (Censor, Technion)**](https://www.youtube.com/playlist?list=PLW3u28VuDAHJNrf3JCgT0GG_rjFVz0-j9)| Academic rigor at its finest. This is where you learn to treat matrices not just as grids of numbers, but as linear operators.|


### 📈 Calculus & Optimization (The Nervous System)
| Resource | Why it's here |
| :--- | :--- |
| [**Essence of Calculus (3B1B)**](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr) | A good visual introduction to different calculus topics.
| [**Calculus One (Fowler, Ohio State)**](https://www.youtube.com/playlist?list=PLaLOVNqqD-2H1OJRzQDqYjGjM-XeJCALw) | Unrivaled conceptual clarity. If you want to understand how a model 'learns' via gradients without getting lost in the notation, start here.|
| [**Calculus Two (Fowler, Ohio State)**](https://www.youtube.com/playlist?list=PLaLOVNqqD-2GXdakC-Sl2qJ0vl6g0lawb) | A beginner-friendly deep dive into sequences and series. |
| [**Calculus 1 (Censor, Technion)**](https://www.youtube.com/playlist?list=PLW3u28VuDAHJymExTBCNnaI6TymzRGsUV) | For those looking to take their calculus rigor to the next level. |
| [**Calculus 2 (Censor, Technion)**](https://www.youtube.com/playlist?list=PLW3u28VuDAHLWNxKyfoBQSVBp-fhWrDr0) | Multivariate calculus. |


### 🎲 Probability and Statistics
| Resource | Why it's here |
| :--- | :--- |
| [**Probability Bootcamp (Brunton, UW)**](https://www.youtube.com/playlist?list=PLMrJAkhIeNNR3sNYvfgiKgcStwuPSts9V) | Good and varied selection of intro to intermediate topics. |
| [**Fundamentals (StatQuest)**](https://www.youtube.com/playlist?list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9) | Intuitive visuals and coverage of most fundamental topics|
| [**Statistics (Organic Chem Tutor)**](https://www.youtube.com/playlist?list=PL0o_zxa4K1BVsziIRdfv4Hl4UIqDZhXWV) | Good and varied selection of intro to intermediate topics. |
| [**Econometrics 1 (Ben Lambert)**](https://www.youtube.com/playlist?list=PLwJRxp3blEvZyQBTTOMFRP_TDaSdly3gU) | A fantastic Khan-Academy-style introduction to Econometrics and Time Series. |
| [**Econometrics 2 (Ben Lambert)**](https://www.youtube.com/playlist?list=PLwJRxp3blEvb7P-7po9AxuBwquPv75LjU) | Part 2. |


### 🤖 Machine Learning
| Resource | Why it's here |
| :--- | :--- |
| [**Machine Learning (Ng, Stanford)**](https://www.youtube.com/playlist?list=PLiPvV5TNogxIS4bHQVW4pMkj4CHA8COdX) | THE original introductory ML playlist, worth it despite its low video resolution by today's standards. |
| [**Statistical Learning (StatQuest)**](https://www.youtube.com/playlist?list=PLblh5JKOoLUICTaGLRoHQDuF_7q2GfuJF) | A gentle and visual introduction to most of the core topics in classical statistical learning. |
| [**Machine Learning I (GaTech)**](https://www.youtube.com/playlist?list=PLAwxTw4SYaPl0N6-e1GvyLp5-MUMUjOKo) | A friendly playlist focused on supervised learning. |
| [**Machine Learning II (Ng, Stanford)**](https://www.youtube.com/playlist?list=PLoROMvodv4rMiGQp3WXShtMGgzqpfVfbU) | Suitable for advanced undergraduates or junior graduate students in ML. |
| [**Learning from Data (Mostafa, Caltech)**](https://www.youtube.com/playlist?list=PLnIDYuXHkit4LcWjDe0EwlE57WiGlBs08) | An introduction to Learning Theory. |


---

## ⌛ Level 2: White-box Literature
![Status: Curating](https://img.shields.io/badge/Status-Curating-orange)

*Content currently being selected. This section will cover the transition from Black-Box ensembles to inherently interpretable architectures, visitng XAI tools along the way as an occasionally useful middle-ground or complementary approach.*

> **Sneak Peek:** We will be covering the seminal works of the world leading White-box AI Schools of Thought: Stanford (Friedman, Hastie, Tibshirani), Wisconsin-Madison (Loh, Zhang, Sankaran), Duke (Rudin), UC Berkeley (Breiman), and more.

---

## ⏳ Level 3: TRUST™ Architecture
![Status: Planned](https://img.shields.io/badge/Status-Planned-red)

*The final frontier: Scaling theory into a production-grade framework for high-stakes healthcare, banking and regulatory compliance.*
