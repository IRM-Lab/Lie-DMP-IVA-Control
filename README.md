# Lie-DMP-IVA-Control
Implementation of Lie-DMPs and Improved Variable Admittance (IVA) control for compliant robotic assembly tasks on UR5e.
# Robotic Assembly Skill Learning with Lie-Theory-Based DMPs and Variable Admittance Control

[![Paper](https://img.shields.io/badge/Paper-Elsevier-blue.svg)](你的论文链接/DOI)
[![Video](https://img.shields.io/badge/Video-Bilibili%2FYouTube-red.svg)](你的视频链接)

> [cite_start]This repository serves as the multimedia presentation page for the paper **"Robotic assembly skill learning with lie-theory-based dynamic movement primitives and variable admittance control"** (Mechanism and Machine Theory, 2026)[cite: 1, 7, 8].

## 🎥 Experimental Demonstrations

*(请在这里插入一张 UR5e 机械臂成功完成装配的高质量 GIF 动图)*
![Assembly Demo](你的动图链接.gif)

[cite_start]In our experiments, the proposed framework was deployed on a UR5e manipulator to perform typical peg-in-hole assembly tasks[cite: 306]. 

**Full Video Demonstration:**
* [Watch on YouTube](你的YouTube链接)
* [Watch on Bilibili](你的Bilibili链接)

---

## 📖 Overview of Methodology

[cite_start]This project explores a learning and control framework to enhance the adaptability and compliance of robotic assembly tasks[cite: 18]. The system consists of two main contributions:

1. [cite_start]**Lie-DMPs (Trajectory Planning):** A novel Dynamic Movement Primitives framework formulated using Lie theory[cite: 21]. [cite_start]It enables the unified encoding and reproduction of both position and orientation at each assembly point[cite: 22]. [cite_start]This approach preserves the geometric features of the human demonstration while allowing smooth generalization to new target poses[cite: 70].
2. [cite_start]**Improved Variable Admittance (IVA) Control:** An active compliance control scheme that uses contact wrench feedback to adjust the assembly trajectory[cite: 22, 23]. [cite_start]By integrating adaptive stiffness and energy-consistent compensation damping, the controller effectively dissipates virtual power and maintains system passivity[cite: 78, 79]. [cite_start]Experimental results show a 78.6% reduction in peak impact force during the contact phase[cite: 24].

## 📊 System Architecture & Results

*(建议放上论文中的图 2：设计的 IVA 控制器原理图)*
![Control Architecture](你的控制系统框图链接.png)
[cite_start]*Fig 1. Schematic of the designed Improved Variable Admittance (IVA) controller[cite: 254].*

*(建议放上论文中的图 4/5：Lie-DMPs 轨迹泛化对比图)*
![Trajectory Generalization](你的轨迹泛化对比图链接.png)
[cite_start]*Fig 2. Generalization comparison of classical DMPs and Lie-DMPs[cite: 409].*

---

## 📝 Citation

If you find our work helpful for your research, please consider citing it:

```bibtex
@article{fu2026robotic,
  title={Robotic assembly skill learning with lie-theory-based dynamic movement primitives and variable admittance control},
  author={Fu, Zhongtao and Li, Longhuan and Wang, Yujia and Spyrakos-Papastavridis, Emmanouil and Li, Miao and Chen, Xubing and Dai, Jian S.},
  journal={Mechanism and Machine Theory},
  volume={227},
  pages={106497},
  year={2026},
  publisher={Elsevier}
}
