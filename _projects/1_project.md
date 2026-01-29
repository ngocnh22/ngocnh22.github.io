---
layout: page
title: Fish Growth Measurement in Indoor Aquaculture
description: AI-driven growth monitoring using Light-Emitting Grid Panels for low-light environments.
img: assets/img/Fish_measure/wf.png
importance: 1
category: Research & Publications
---

## **Abstract**

This research introduces a solution within the **Smart Aqua Farm** ecosystem, integrating AI and IoT. The objective is to automate monitoring of fish size in low-light indoor tanks to predict harvest timing.

---

## **Introduction**

Manual measurement in aquaculture causes stress and is labor-intensive. We propose a **light-emitting grid panel** at the tank bottom to provide a physical reference and improve contrast.

---

## **Method**

The system uses an overhead camera and an LED grid panel.

<div class="row justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0 text-center">
        <img src="/assets/img/system_diagram.png" class="img-fluid rounded z-depth-1" alt="System Architecture" style="max-width: 100%;">
    </div>
</div>
<div class="caption">
    <strong>Figure 1:</strong> System Architecture integration.
</div>


1. **Hardware:** Overhead camera and LED grid panel.
2. **Software:** Instance segmentation and pixel-to-mm conversion.

---

## **Results**

Experimental trials demonstrated over **90% accuracy**.

<div class="row mt-3 justify-content-sm-center">
    <div class="col-sm-10 mt-3 mt-md-0">
        <div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 10px;">
            <iframe 
                src="https://www.youtube.com/embed/w2CnC5Q6NcM" 
                style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border:0;" 
                allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" 
                allowfullscreen>
            </iframe>
        </div>
    </div>
</div>
<div class="caption">
    <strong>Video 1:</strong> Real-time fish segmentation demonstration.
</div>

---

## **References**

1. **Nguyen Ngoc Huynh**, M. Jun, and H. Jeong. (2024). *Effect of Light-Emitting Grid Panel on Indoor Aquaculture for Measuring Fish Growth*. **Sensors**, 24(3), 852.
---
