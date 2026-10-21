# Rikhil Amonkar
**Computer Science @ Drexel University** · Data Science Minor

---

## About
Software developer focused on low-latency C++ systems, machine learning, and LLM research. Currently a Software Developer Co-op at Susquehanna International Group on the TORQ team. Previously a Machine Learning Engineer Co-op at Lockheed Martin, Sikorsky, working on real-time aerial detect-and-avoid systems, and currently Head of Computer Vision & Software at Exo Dynamics, an early-stage autonomous drone startup. Undergraduate AI Researcher at Drexel's HazLab, co-first author on a COLM 2026 workshop paper benchmarking LLM reasoning failures on constraint-satisfaction tasks.

Interests outside of work: bodybuilding, making music in FL Studio, and poker.

---

## Experience

**Software Developer Co-op, TORQ** — Susquehanna International Group *(Sept 2026 – Mar 2027)*
Bala Cynwyd, PA

**Machine Learning Engineer Co-op** — Lockheed Martin, Sikorsky *(Oct 2025 – Mar 2026)*
Stratford, CT

**Software Developer, Head of CV** — Exo Dynamics Co. *(Jan 2026 – Present)*
Philadelphia, PA

**Undergraduate AI Researcher** — Drexel University, HazLab *(Jan 2025 – Present)*
Philadelphia, PA

---

## Skills
**Programming Languages** — C++ (17/20), C, Python, Java, Bash, SQL
**Systems & Tools** — SQLite3, CMake, GoogleTest, Catch2, Pybind11, Linux, Git, Docker, GitHub Actions
**Machine Learning** — PyTorch, TensorRT, OpenCV, NumPy, YOLO, Vision Transformers, Hugging Face, Scikit-learn

---

## Projects

**Quant-Based DSL Backtesting Engine (C++20)** *(Feb 2026 – Apr 2026)*
Built a C++ lexer/parser for a custom DSL, compiling strategies into structured executable rules for a backtesting engine. Assembled a two-stage event loop with next-open execution, live indicator updates, and realized/unrealized P&L tracking. Benchmarked 4 custom strategies and 6 ticker symbols across 20 years of daily bars, achieving 23K+ events/sec.

**[Custom PyTorch LayerNorm C++ Extension](https://github.com/rikhil-amonkar/pytorch-cpp-layernorm-accelerator)** *(Dec 2025 – Jan 2026)*
Built a LayerNorm forward/backward pass in C++20 with full autograd via Pybind11, validated to 1e-7 tolerance. Cut runtime 44–58% by fusing backward-pass math to avoid extra tensor allocations, found via chrono-timed benchmarks. Benchmarked CPU vs. Apple GPU (MPS) on a ten-case Catch2 test suite, finding up to 53% speedup at scale.

**[LLM Planning Research](https://github.com/rikhil-amonkar/llm-csp)**
Evaluation framework benchmarking SOTA LLMs on formal constraint-planning tasks, underlying the HazLab COLM workshop paper.

**[DragonFlow](https://github.com/rikhil-amonkar/dragonflow)**
Full-stack course scheduling platform for Drexel students. Gradient Boosting model (~90% val accuracy) with Flask inference API, built as Product Owner for a 4-member team.

---

## Publications
Amonkar, R.\*, Kayan, C. E.\*, Lai, Q., Le Bras, R., and Zhang, L., "A Reality Check of Language Models as Formalizers on Constraint Satisfaction Problems," COLM 2026 Workshop on Efficient Reasoning; arXiv:2505.13252, 2025. (\*equal contribution)

Tehrani, N. D., Amonkar, R., Weintraub, J., Carlson, S., and Cherepinsky, I., "Vision-based Non-Cooperative Intruder Detect and Avoid using Deep Learning Techniques," Proceedings of the Vertical Flight Society's 82nd Annual Forum & Technology Display, (Forum 82), West Palm Beach, FL, USA, May 5–7, 2026.

---

## Connect
[LinkedIn](https://www.linkedin.com/in/rikhil-amonkar/) · [Email](mailto:rikhilma@gmail.com) · [GitHub](https://github.com/rikhil-amonkar)
