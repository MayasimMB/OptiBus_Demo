# 🚍 OptiBus Demo

This repository contains the public demonstration of **OptiBus**, an AI-Based School Bus Routing Optimization System.

It includes the project demonstration and the proposed user interface design. The complete implementation, research source code, trained models, and datasets are **not included** in this repository.

---

# About the Project

OptiBus is an AI-based school bus routing optimization system that dynamically generates optimized school bus routes based on students' geographical locations and daily attendance.

The proposed framework integrates **K-Means++ Student Clustering**, **Adaptive Large Neighborhood Search (ALNS)**, and **Proximal Policy Optimization (PPO)** to improve routing efficiency while satisfying school transportation constraints.

---

# Project Features

- Hybrid optimization framework integrating **Adaptive Large Neighborhood Search (ALNS)** with **Proximal Policy Optimization (PPO)** for intelligent route optimization.
- Automatic student clustering and bus assignment using **K-Means++** based on students' geographical locations.
- Dynamic route generation that adapts to daily student attendance.
- Route optimization while satisfying school transportation constraints, including bus capacity and maximum student ride time.
- Reduced travel distance, travel time, and estimated fuel consumption through optimized route planning.
- Parent attendance reporting to automatically exclude absent students before daily route generation.
- Interactive demonstration of the complete transportation workflow and optimized routes.

---

# Technologies Used

## Programming Language

- Python

## AI & Optimization

- K-Means++ Student Clustering
- Adaptive Large Neighborhood Search (ALNS)
- Proximal Policy Optimization (PPO)

## Libraries

- Scikit-learn
- Stable-Baselines3
- Pandas
- NumPy
- Matplotlib

## APIs & Services

- Google Maps API – Travel distance and travel time retrieval.
- TomTom API – Travel distance and travel time retrieval.
- Twilio API – Parent notification integration.

## UI Design

- Figma

## Development Environment

- Google Colab

---

# My Contributions

I contributed to the project through the following responsibilities:

- Generated the travel distance and travel time matrices using the TomTom API to build the transportation dataset for student locations.
- Preprocessed, analyzed, and explored the transportation dataset to prepare it for model development.
- Evaluated multiple student clustering algorithms, including an Agglomerative Clustering model that I developed and tested for our routing problem. Based on the performance evaluation, K-Means++ was selected as the final clustering method.
- Implemented the Adaptive Large Neighborhood Search (ALNS) algorithm for school bus route optimization.
- Developed and trained a Proximal Policy Optimization (PPO) reinforcement learning agent and integrated it with ALNS to enhance the performance and stability of the route optimization framework.
- Integrated the Twilio API to support parent notification services.
- Designed the Parent and Driver application interfaces using Figma.
- Contributed to writing the project's technical report and documentation.

---

# Repository Overview

## 📁 Demo

Contains the public demonstration of the OptiBus system, including:

- Demonstration video.
- Demonstration workflow.
- Google Drive link for faster video access.

## 📁 System_Interface

Contains the proposed user interface design of the OptiBus mobile application, including:

- Parent application interfaces.
- Driver application interfaces.
- Interface preview.
