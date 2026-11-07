# Lidor Zino

**Electrical Engineer** · autonomous AI agents · ML for medical signals and images  
System Validation Engineer at **DriveNets** · B.Sc. in Electrical Engineering, **Technion**.  
I build AI agents that run unattended research loops overnight, and I apply deep learning to medical signals and images.

- 📫 **Email**: ljinoo0@gmail.com
- 💼 **LinkedIn**: [linkedin.com/in/lidorzino](https://www.linkedin.com/in/lidorzino)

---

## Selected Work

- **Autonomous Research Agent: Two-Deletion-Correcting Codes** · [repo](https://github.com/LZguy/two-deletion-code-16)  
  An unattended overnight agent (Claude Code) with a task spec, persistent state, a research journal and a human-escalation channel. The agent built a numba local search and an exact large-neighbourhood search (HiGHS MILP), run as a parallel portfolio.  
  **Result**: a 219-codeword two-deletion-correcting code of length 16, **#1 on the EinsteinArena leaderboard** (previous record 218; literature value 215). Every candidate is checked by two independent verifiers.

- **SonoVision: Fetal Ultrasound Plane Classification** (Technion SIPL)  
  Swin Transformer classifier for 6 fetal planes, with a 5-fold ensemble, MixUp/CutMix and focal loss.  
  **Results**: **95.45%** test accuracy (**96.28%** balanced). **Thomas Schwartz Award**; paper submitted to **ISBI 2027**.  
  _Collaborator_: Matan Ashuach.

- **CardioSense: ECG Arrhythmia Detection (3 models)** · [repo](https://github.com/MatanAshuach/CardioSense)  
  Benchmarked **Transformer**, **Transformer+TCN** and **Transformer+TCN+BiLSTM** with attention pooling and a per-feature softmax fusion gate.  
  **Results**: test accuracy up to **99.8%** on ECG5000; the tri-branch model shows the strongest validation PR-AUC.  
  _Role_: modeling, training pipeline, evaluation and calibration. _Collaborator_: Matan Ashuach.

- **Verilog → DFHDL Translator (prototype)**  
  Translator from synthesizable Verilog to higher-level **DFHDL** (parsing → IR → codegen), with an LLM-automated flow (OpenAI API) and formal equivalence checks in EQY.

- **Earlier hardware work**: SAT-based gate-level equivalence checking (MiniSat, CNF from Verilog netlists); a parametric Booth multiplier in DFHDL, verified with testbenches.

---

## Skills

**ML / DL**: PyTorch, NumPy/SciPy, scikit-learn, pandas, matplotlib  
**Agents & LLMs**: Claude Code (unattended multi-session agents), OpenAI API  
**Languages**: Python, C/C++, Verilog/SystemVerilog, (DF)HDL, VHDL  
**Hardware & lab**: digital design and verification, power validation, lab automation (VISA/SCPI)  
**Tools**: Linux, Git/GitHub, VS Code, Jupyter

---

## What I enjoy

- Giving AI agents hard, open problems, and verifying what comes back
- Bringing ML to real-world medical signals and images
- Hardware–software co-design
