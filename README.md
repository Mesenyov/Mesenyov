### Hi there! I'm Alexey 👋

I am an aspiring **Machine Learning Engineer** passionate about **Computer Vision**. I enjoy solving complex engineering problems where standard "out-of-the-box" solutions fall short.

---

### 🔭 Flagship Project: PCB Defect Detection System (AOI)

Currently, I am developing an Automated Optical Inspection (AOI) system for detecting manufacturing defects on printed circuit boards.

**The Challenge:** Standard object detectors (like YOLO) fail to detect "Unknown" defects that were not present in the training set.
**Our Solution:** A two-stage hybrid architecture combining **Siamese Networks** for localization and **Metric Learning** for classification.

*   **Architecture:** Custom Siamese U-Net + EfficientNet-B0 Backbone.
*   **Methodology:** ArcFace Loss for compact feature clustering + Prototypical Networks.
*   **Key Result:** Achieved **98.5% Recall** (vs 93.4% for YOLOv8m) and successfully implemented **Zero-shot detection** for unknown anomalies.
*   **Deployment:** Real-time inference via FastAPI (~26 FPS on GPU).

🤝 **Collaboration:** This project is being developed in a team with **Efremenko Andrey**.

> 🔒 **Note:** *The source code is currently stored in a private repository due to the ongoing Bachelor's Thesis defense. I am happy to provide access upon request or demonstrate the code during a technical interview.*

---

### 🛠 Tech Stack & Tools

*   **Languages:** Python
*   **DL Frameworks:** PyTorch, Torchvision, Timm
*   **CV Tools:** OpenCV, Albumentations, YOLOv8
*   **Architecture Patterns:** U-Net, Siamese Networks, ArcFace, Autoencoders
*   **Deployment:** FastAPI
*   **Version Control:** Git, Git LFS

---

### 📫 Contact Me

*   **Telegram:** [@Mesenyov](https://t.me/Mesenyov)
*   **Email:** mesenyovalexey@yandex.ru
