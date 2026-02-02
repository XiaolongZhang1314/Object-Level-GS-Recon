# Research-on-Object-Level-Reconstruction-Based-on-3D-Gaussian-Models


This repository presents an object-level 3D reconstruction framework based on
3D Gaussian Splatting, designed to accurately model individual objects from
multi-view RGB-D observations.

The proposed method focuses on probabilistic object modeling and produces
clean, compact Gaussian representations suitable for downstream analysis and
rendering.

---

## 🔍 Overview

We perform object-level reconstruction by optimizing a set of 3D Gaussians
constrained by multi-view image observations.
Each Gaussian is associated with an object membership probability, enabling
robust separation between foreground objects and background regions.

The overall reconstruction pipeline is illustrated below.

![pipeline](assets/pipeline.png)

---

## 🎥 Visual Results

### Reconstruction Results

<p align="center">
  <img src="assets/12.png" width="45%" />
  <img src="assets/42.png" width="45%" />
</p>

<p align="center">
  <img src="assets/lingbujian.png" width="45%" />
  <img src="assets/fadongji.png" width="45%" />
</p>

<!-- ![result1](assets/12.png)
![result1](assets/42.png)
![result2](assets/lingbujian.png)
![result2](assets/fadongji.png) -->
<!-- ![result2](assets/result2.png) -->

### Video Demo
<!-- [![Video Demo](assets/video_teaser.png)](https://youtu.be/XXXXXXX) -->
[![Video Demo](assets/lingbujian.mp4)]

---

## 📂 Code Availability

The code will be released after paper acceptance.

---

## 📄 Citation


