# Deepfake Detection Using Hybrid Deep Learning Framework

## Overview

This project presents a **hybrid deepfake detection framework** that leverages CNN-based feature extraction and physiological cues to improve detection accuracy and robustness. Deepfake media, which is increasingly realistic, poses serious cybersecurity and misinformation risks. Our approach combines multiple neural networks with Eye Movement Analysis to enhance detection effectiveness.

## Features

- **Hybrid Model Architecture:** Integrates ResNet50 and MesoNet4 for high-level spatial and low-resolution feature detection.  
- **Physiological Cue Analysis:** Uses blink rate and gaze shift inconsistencies to improve model performance.  
- **High Accuracy:** Achieves **97.61% accuracy** on multiple datasets including Deepfake-and-Real Images, UADFV, and FaceForensics++.  


## Architecture

- **ResNet50:** Extracts high-level spatial features.  
- **MesoNet4:** Optimized for detecting low-resolution manipulations.  
