# Rikhil Amonkar
**Computer Science @ Drexel University** · Data Science Minor

---

## About
Software developer focused on machine learning, computer vision, and LLM systems. Incoming Software Developer Co-op at Susquehanna International Group (TORQ team). Previously a Machine Learning Engineer Co-op at Lockheed Martin, Sikorsky, working on real-time aerial detect-and-avoid systems, and currently Head of Computer Vision & Software at Exo Dynamics, an early-stage autonomous drone startup. Undergraduate AI Researcher at Drexel's HazLab, first-author on a published benchmark of LLM reasoning failures on constraint-planning tasks.

Interests outside of work: bodybuilding, making music in FL Studio, and poker.

---

## Experience

**Incoming Software Developer Co-op, TORQ** — Susquehanna International Group *(Sept 2026 – Mar 2027)*
Bala Cynwyd, PA

**Machine Learning Engineer Co-op** — Lockheed Martin, Sikorsky *(Oct 2025 – Mar 2026)*
Stratford, CT
- Developed a real-time vision transformer trained on 40K+ drone images for helicopter intruder detection and avoidance, improving bounding-box accuracy by 80% relative to baseline in high-motion camera conditions
- Implemented a Python-based state estimation module using 2D Kalman filtering and OpenCV-based multi-frame motion-compensated background subtraction, cutting inference jitter by 45% and false positives by 25%
- Constructed a scalable 2D-to-3D ship deck pose estimation pipeline integrating YOLO-based detection with matrix transformation layers, trained on 100K+ synthetic renders and validated to ≤1° rotational error

**Software Developer, Head of CV** — Exo Dynamics Co. *(Jan 2026 – Present)*
Philadelphia, PA
- Built a real-time Python-based human detection system for drone perception, achieving 88% accuracy on 180K+ images
- Tested obstacle-avoidance logic in ArduPilot SITL, cutting per-step drift by up to 97% against mid-flight object insertions
- Applied EMA smoothing to a ToF sensor–Jetson Orin Nano distance estimation setup, reducing reading noise by 67%

**Undergraduate AI Researcher** — Drexel University, HazLab *(Jan 2025 – Present)*
Philadelphia, PA
- Led a first-author paper benchmarking 4 state-of-the-art LLMs across 3 constraint-planning tasks, characterizing reasoning failures where models waste tokens over-solving instead of producing executable Python code
- Built an LLM-as-judge pipeline (Gemini-2.5-Pro) classifying solver-like reasoning traces at the chunk level across 4 prompting complexity levels, finding reasoning failures occupied up to 76% of pre-code traces
- Cut excess token counts up to 46% and raised accuracy by up to 14% by removing such reasoning from traces

---

## Skills
**Programming Languages** — C++ (17/20), C, Python, Java, Bash
**Systems & Tools** — Pybind11, CMake, Catch2, Linux, Git, Docker, GitHub Actions
**Machine Learning** — PyTorch, TensorRT, OpenCV, NumPy, YOLO, Vision Transformers, Hugging Face, Scikit-learn

---

## Projects

**Quant-Based DSL Backtesting Engine (C++20)** *(Feb 2026 – Apr 2026)*
Built a C++ lexer/parser for a custom DSL, compiling strategies into structured executable rules for a backtesting engine. Assembled a two-stage event loop with next-open execution, live indicator updates, and realized/unrealized P&L tracking. Benchmarked 4 custom strategies and 6 ticker symbols across 20 years of daily bars, achieving 23K+ events/sec.

**[Custom PyTorch LayerNorm C++ Extension](https://github.com/rikhil-amonkar/pytorch-cpp-layernorm-accelerator)** *(Dec 2025 – Jan 2026)*
Built a LayerNorm forward/backward pass in C++20 with full autograd via Pybind11, validated to 1e-7 tolerance. Cut runtime 44–58% by fusing backward-pass math to avoid extra tensor allocations, found via chrono-timed benchmarks. Benchmarked CPU vs. Apple GPU (MPS) on a ten-case Catch2 test suite, finding up to 53% speedup at scale.

**[LLM Planning Research](https://github.com/rikhil-amonkar/llm-csp)**
Evaluation framework benchmarking SOTA LLMs on formal constraint-planning tasks, underlying the HazLab first-author paper.

**[OncoDeepMind](https://github.com/rikhil-amonkar/oncodeepmind)**
End-to-end PyTorch pipeline predicting cancer drug response from GDSC genomic data. 32% baseline improvement, deployed with FastAPI for real-time inference.

**[DragonFlow](https://github.com/rikhil-amonkar/dragonflow)**
Full-stack course scheduling platform for Drexel students. Gradient Boosting model (~90% val accuracy) with Flask inference API, built as Product Owner for a 4-member team.

**[Asteroid Trajectory Predictor](https://github.com/rikhil-amonkar/asteroid-trajectory-predictor)**
ML model trained on NASA asteroid data to predict impact probability for potential threats.

**[Heart Failure Predictor](https://github.com/rikhil-amonkar/heart-failure-predictor-ml)**
Interactive web app with a custom-trained model predicting heart failure probability.

---

## Publications
Tehrani, N. D., Amonkar, R., Weintraub, J., Carlson, S., and Cherepinsky, I., "Vision-based Non-Cooperative Intruder Detect and Avoid using Deep Learning Techniques," Proceedings of the Vertical Flight Society's 82nd Annual Forum & Technology Display, (Forum 82), West Palm Beach, FL, USA, May 5–7, 2026.

Amonkar, R.*, Kayan, C. E.*, Lai, Q., Le Bras, R., and Zhang, L., "A Reality Check of Language Models as Formalizers on Constraint Satisfaction Problems," arXiv preprint, arXiv:2505.13252, 2025.

---

## Certifications
- Generative AI with Large Language Models — DeepLearning.AI & AWS (Coursera) · Aug 2024
- Launching into Machine Learning — Google Cloud (Coursera) · Apr 2025

---

## Connect
[LinkedIn](https://www.linkedin.com/in/rikhil-amonkar/) · [Email](mailto:rikhilma@gmail.com) · [GitHub](https://github.com/rikhil-amonkar)
