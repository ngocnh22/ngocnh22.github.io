---
layout: page
title: Fish Growth Measurement in Indoor Aquaculture
description: AI-driven growth monitoring using Light-Emitting Grid Panels for low-light environments.
img: assets/img/Fish_measure/wf.png
importance: 1
category: Research & Publications
---

## **Abstract**
This research introduces a solution within the **Smart Aqua Farm** ecosystem, integrating Artificial Intelligence (AI) and the Internet of Things (IoT). The primary objective is to automate the monitoring of average fish size and area in real-time, even in the low-light conditions characteristic of indoor aquaculture tanks. This system aims to reduce labor intensity and provide accurate harvest timing predictions.

---

## **Introduction**
In traditional aquaculture, measuring fish size and weight is often performed manually, causing stress to the fish and being labor-intensive for operators. The greatest challenge in automation is poor indoor lighting and fish overlapping while swimming. This project proposes a **light-emitting grid panel** at the tank bottom to serve as a physical size reference and improve image contrast for segmentation.

---

## **Method**
The system integration utilizes a specialized hardware setup and a deep learning-based software pipeline:

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        {% include figure.html path="assets/img/system_diagram.png" title="System Architecture" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    <strong>Figure 1:</strong> System Architecture. Integration of the LED grid panel with an overhead camera system.
</div>

1. **Hardware:** Overhead camera and a light-emitting LED grid panel at the tank bottom.
2. **Software:** Image preprocessing, instance segmentation, and pixel-to-mm conversion.

---

## **Results**
Experimental trials demonstrated over **90% accuracy**. Below is the real-time processing output:

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        <div class="embed-responsive embed-responsive-16by9">
            <iframe 
                src="https://www.youtube.com/embed/w2CnC5Q6NcM" 
                title="YouTube video player" 
                frameborder="0" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                allowfullscreen 
                style="width: 100%; height: 400px; border-radius: 10px;">
            </iframe>
        </div>
    </div>
</div>
<div class="caption">
    <strong>Video 1:</strong> Real-time fish segmentation and growth measurement demonstration.
</div>

---

## **References**
1. **Nguyen Ngoc Huynh**, M. Jun, and H. Jeong. (2024). *Effect of Light-Emitting Grid Panel on Indoor Aquaculture for Measuring Fish Growth*. **Sensors**, 24(3), 852.
2. Frameworks: Deep Learning models implemented via PyTorch for high-precision Instance Segmentation.
---
