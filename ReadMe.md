<h1 align="center">Mohamed Ashraf</h1>

<p align="center">
  <b>AI/ML Engineer · Embedded Systems Background</b><br/>
  Computer vision, ML pipelines, and cloud MLOps, built on a foundation of robotics and hardware.
</p>

<p align="center">
  <a href="https://linkedin.com/in/mohamedashraf09"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:mohamed.ashraf.sayed10@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://instagram.com/znegga"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat&logo=instagram&logoColor=white" alt="Instagram"/></a>
</p>

---

## About

I'm a Mechatronics Engineering student (class of 2028) and IT Engineer who moved from embedded systems, robotics, and PCB design into applied machine learning. I like problems where software has to make sense of the physical world.

- 🔭 Building **Bordexa**, my graduation project: hand-drawn circuit schematics to KiCad files using computer vision
- 🌱 Learning: Generative AI, advanced deep learning, cloud MLOps
- 🤝 Looking for: collaborators on open-source AI/ML projects, and input on scaling models and MLOps deployment
- 💬 Ask me about: Python, machine learning, model optimization, embedded systems

---

## Featured Project

### 🔌 Bordexa: Hand-Drawn Schematic to Digital Circuit

An end-to-end system that reads a photo of a hand-drawn circuit and produces an editable KiCad schematic.

```mermaid
flowchart LR
    A[Upload image] --> B[OpenCV normalization]
    B --> C[YOLOv8 component detection]
    C --> D[Component masking]
    D --> E[Skeletonization + Hough lines]
    E --> F[NetworkX netlist graph]
    F --> G[KiCad export]
```

- **Detection:** YOLOv8 with transfer learning from a public circuit-symbol dataset, fine-tuned on real hand-drawn samples
- **Topology:** wire and junction extraction with OpenCV, converted into a netlist graph with NetworkX
- **Validation:** graph checks for short circuits and open connections
- **MLOps:** AWS (S3, SageMaker, Lambda) with a feedback loop that feeds user corrections into scheduled re-training
- **Role:** team leader of a six-person team

`Python` `YOLOv8` `OpenCV` `NetworkX` `AWS SageMaker` `Docker` `KiCad`

> 📎 *Repository link coming soon.*

---

## Tech Stack

| Area | Tools |
|---|---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white) |
| **ML / Deep Learning** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) |
| **Data** | ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![Airflow](https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white) ![Flink](https://img.shields.io/badge/Flink-E6526F?style=flat-square&logo=apacheflink&logoColor=white) |
| **Cloud & MLOps** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Git](https://img.shields.io/badge/Git-F05033?style=flat-square&logo=git&logoColor=white) |
| **Hardware** | Embedded systems · Robotics · PCB design (KiCad) |

---

## Focus Areas

- **Computer vision:** object detection, image preprocessing, structure extraction
- **ML engineering:** training, evaluation, model optimization, active learning
- **Cloud MLOps:** containerized inference, scheduled pipelines, drift monitoring
- **Data engineering:** AWS-based pipelines, orchestration, streaming basics

---

## Education & Training

- 🎓 **B.Sc. Mechatronics Engineering**, October 6 University (expected 2028)
- 📚 **Digital Egypt Pioneers Initiative (DEPI):** AWS Data Engineering, ML Foundations, NLP, Generative AI
- 💼 **IT Engineer**, Dar El Oroba Hospital

---

<p align="center">
  <i>"AI is just engineering with a creative brain."</i>
</p>

<!-- Add the GitHub stats cards back once there is meaningful public activity. -->
