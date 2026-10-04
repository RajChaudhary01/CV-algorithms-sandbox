# Lecture [01]: [ Introduction to Computer Vision]
* **Date:** 2026-10-04
* **Main Topics Covered:** Evolution of CV, Machine Vision vs. Computer Vision, Feature Engineering (Heuristics) vs. Deep Learning, AlexNet.

## 📑 Table of Contents
* [1. Core Intuition & Theory](#1-core-intuition--theory)
* [2. Flowchart](#2-flowchart)


---

## 1. Core Intuition & Theory

This section documents the foundational principles of Computer Vision (CV). My objective here is to establish a strong foundation through an end-to-end learning journey, utilizing *Practical Machine Learning for Computer Vision* by O'Reilly and its associated GitHub repository. In the following notes, I explore the formal definition of CV, its evolution, and the historical shift from traditional heuristics to deep learning.

### Machine Vision vs. Computer Vision
While often used interchangeably, there is a core difference:
* **Machine Vision** is system-oriented. It focuses on practical industry applications involving specific hardware integration (cameras, lighting, sensors). *Example: Monitoring wear on a grinding wheel on a factory line.*
* **Computer Vision** is algorithm-oriented. It primarily concerns the development of algorithms to interpret and derive meaning from existing images or video frames. *Example: Facial recognition or autonomous vehicle perception.*

### The Evolution of Computer Vision
* **Early Era (Pre-2010):** Relied heavily on **heuristics** (manually defined rules) and **Feature Engineering**.
* **Filters & Kernels:** Engineers manually designed small matrices (kernels) that scanned across an image to detect specific features like edges or shapes. Edge detection, for instance, identifies transitions in pixel brightness or color. Early CV relied on mathematical logic for this, utilizing tools like the Laplacian, Canny, and Sobel edge detectors.
* **The Scaling Limitation:** Creating rules for every potential edge case (e.g., orientation changes, different lighting, new fonts) is practically impossible and inefficient.

### The Rise of Deep Learning
The paradigm shifted from manual feature extraction to data-driven learning.
* **Machine Learning vs. Deep Learning:** In standard ML, features must be manually extracted and fed to the model. Deep Learning automatically performs both feature extraction and classification from raw data using neural networks. 
* **Network Depth:** A shallow neural network typically contains few hidden layers (around 1-2), whereas deep neural networks utilize multiple layers to automatically capture complex, abstract data patterns.
* **AlexNet (2012):** This was a turning point. It won the 2012 ImageNet challenge with a significantly lower error rate (15.3%) compared to competitors. It popularized the use of GPUs for training, ReLU activation functions, Dropout, and data augmentation.

---

## 2. Flowchart

*(Below is the Miro chart mapping out the core concepts from the lecture)*
![Lecture 0 Miro Map](https://miro.com/app/board/uXjVEek8Xmg=/?share_link_id=865448825613)
![Lecture 1 Miro Map](https://miro.com/app/board/uXjVEek0Ffo=/?share_link_id=88688562113)

## 3. Mathematical Concepts
//

## 4. Debugging
//
