---
layout: page
title: Effect of Light-Emitting Grid Panel on Indoor Aquaculture for Measuring Fish Growth
description: An automated fish growth monitoring system using a light-emitting grid panel and deep learning for low-light indoor environments.
img: assets/img/fish_grid_teaser.jpg
importance: 1
category: research
---

## Abstract
This research introduces a solution within the **Smart Aqua Farm** ecosystem, integrating Artificial Intelligence (AI) and the Internet of Things (IoT). The primary objective is to automate the monitoring of average fish size and area in real-time, even in the low-light conditions characteristic of indoor aquaculture tanks. This system aims to reduce labor intensity and provide accurate harvest timing predictions.

## Introduction
In traditional aquaculture, measuring fish size and weight is often performed manually by sampling just before shipment. This process causes significant stress to the fish and is labor-intensive for operators. 

The greatest challenge in automating this via cameras is that indoor lighting is typically poor, and fish frequently overlap while swimming. This project proposes a **light-emitting grid panel** placed at the bottom of the tank to serve as a physical size reference and to improve image contrast for better segmentation.

## Method
The system consists of several key components:
1. **Hardware:** - A video camera mounted above the tank.
   - A light-emitting LED grid panel placed at the bottom of the tank, acting as a direct physical ruler within the captured frames.
2. **Software Pipeline:**
   - **Boundary Validation:** Checking if the fish is fully contained within the grid area.
   - **Overlap Classification:** Algorithms to automatically distinguish between individual fish and overlapping groups to eliminate noise.
   - **Segmentation & Measurement:** Utilizing Deep Learning for instance segmentation of the fish body, followed by a pixel-to-millimeter (mm) conversion based on the known grid scale.

## Result
Experimental trials using both mock-ups and live fish in dark environments demonstrated:
- **Accuracy:** The system achieved over **90% accuracy** in measuring length and surface area.
- **Performance:** Real-time processing allows farmers to predict required feed amounts and estimate the time needed for fish to reach target sizes.
- **Robustness:** The system effectively overcomes the limitations of standard camera systems in low-light indoor settings.

## References
1. **Nguyen Ngoc Huynh**, Myoungjae Jun, and Hieyong Jeong. (2024). *Effect of Light-Emitting Grid Panel on Indoor Aquaculture for Measuring Fish Growth*. **Sensors**, 24(3), 852.
---
