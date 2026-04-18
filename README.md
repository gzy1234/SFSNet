<div align="center">

# SFSNet: Object Detection in Adverse Weather via Active Frequency-Spatial Feature Recovery

**Zhiyi Gu · Yingdong Ma***

College of Computer Science, Inner Mongolia University

[![Paper](https://img.shields.io/badge/Paper-Springer-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)]()

</div>

---

## 📢 News

- **​[2026-04]​** 🎉 Paper submitted to *Multimedia Systems*. Code will be released upon acceptance.

---

## Abstract

Object detection in adverse weather remains challenging as visual corruption severely impairs semantic feature extraction. Existing "Restore-then-Detect" paradigms often smooth high-frequency features which are essential for visual recognition. To tackle this problem, we propose **SFSNet**, a real-time detector based on an active feature recovery mechanism with three main modules ...

> Full abstract available in the paper.

---

## Overall Architecture

<!-- 替换为你的 Fig.2 架构图路径 -->
<p align="center">
  <img src="assets/architecture.png" width="90%">
</p>

---

## Qualitative Results

<p align="center">
  <img src="assets/rtts_vis.png" width="45%">
  &nbsp;
  <img src="assets/exdark_vis.png" width="45%">
</p>

<p align="center">
  <em>Left: Visual comparison on RTTS (Haze). Right: Visual comparison on ExDark (Low-Light).</em>
</p>

---

## Quantitative Results

| Method | RTTS mAP | ExDark mAP |
|---|---|---|
| YOLOv8s (Baseline) | 45.3 | 50.0 |
| LR-YOLOv8 | 53.2 | 54.5 |
| **SFSNet + YOLOv8s (Ours)​** | **56.8** | **58.8** |

---

## Code

> 🚧 **Coming Soon** — Code will be released upon paper acceptance.

---

## Citation

If you find this work useful, please consider citing:

```bibtex
@article{gu2026sfsnet,
  title     = {SFSNet: Object Detection in Adverse Weather via Active Frequency-Spatial Feature Recovery},
  author    = {Gu, Zhiyi and Ma, Yingdong},
  journal   = {Multimedia Systems},
  year      = {2026}
}
```

---

## Acknowledgements

This work was supported by the Natural Science Foundation of Inner Mongolia Autonomous Region under Grant 2025MS06010.
