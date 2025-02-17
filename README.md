# **StyloMorph**

**Transform Faces into Art with Precision and Simplicity**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pXr8tnGr2tJlkkR5O0EukndqJD7_146Q?usp=sharing) [![Research Paper](https://img.shields.io/badge/Publication-Research_Paper-blue)](https://ieeexplore.ieee.org/document/10866661)

## **Overview**

<p align="center">
    <img width="400" src="https://github.com/user-attachments/assets/9e5b3b58-b170-4200-bd98-f3d237a809ea">
</p>

**StyloMorph** is a streamlined face stylization system designed to transform facial features into artistic styles while preserving unique characteristics. Powered by advanced models like **StyleGAN2** and **e4e**, StyloMorph ensures high-quality results with minimal computational requirements, making artistic transformations accessible to everyone.

### **Key Features**
- **One-Shot Stylization**: Transforms faces with just a single reference style image.
- **High-Quality Outputs**: Maintains facial details while applying stylized transformations.
- **Efficient Processing**: Uses **e4e encoding** for optimized GAN inversion, reducing computation time.
- **Real-Time Stylization**: Works efficiently even on resource-limited hardware.
- **Customizable Style Intensity**: Fine-tune outputs with adjustable parameters.
- **Supports Multi-Shot Stylization**: Extends capabilities to multiple reference styles.
- **User-Friendly**: Seamless integration with Google Colab for easy setup and usage.
  
---

## **Published Work**
This research has been accepted at the **3rd DELCON, 2024 IEEE International Conference on Advancing Technology for Sustainable Development** and published in **IEEE**.<br>
[📑Research Paper](https://ieeexplore.ieee.org/document/10866661))<br>
**Title:** One-Shot Stylization for Transformative Facial Art using StyloMorph
**Conference:** 2024 3rd Edition of IEEE Delhi Section Flagship Conference (DELCON)
**Publisher:** IEEE

---
## **How It Works**

### **Architecture of StloMorph**
<p align="center">
    <img width="600" src="https://github.com/user-attachments/assets/4e255708-005a-48f1-b9f2-ecc2bb87f6cd">
</p>

StyloMorph uses a simple yet powerful pipeline for face stylization:

1. **Facial Feature Extraction**: Uses **DLib Shape Predictor** (68 facial landmarks) to detect key facial features.

<p align="center">
    <img width="400" src="https://github.com/user-attachments/assets/1ab86021-420d-4caf-89ad-1a9256cd8201">
</p>

2. **Latent Space Encoding**: Maps facial features into **StyleGAN2’s latent space** using the **e4e encoder**.

<p align="center">
    <img width="400" src="https://github.com/user-attachments/assets/6918adc3-23c2-444f-898f-54d6ceab1ae0">
</p>

3. **Style Transfer**: Applies artistic transformations while preserving facial identity.

<p align="center">
    <img width="500" src="https://github.com/user-attachments/assets/6f30748b-625f-4378-8b9a-05435283f608">
</p>

 4. **Output Generation**: Generates realistic, high-resolution stylized images.

<p align="center">
    <img width="500" src="https://github.com/user-attachments/assets/c616e77e-6504-422c-8155-8e2c8f8bbe4b">
</p>

🔹 **Core Pre-trained Models Used**:
- **StyleGAN2-FFHQ Config-F**: Optimized for realistic face generation.
- **e4e-FFHQ Encode**: Enables precise editing in latent space.
- **DLib 68-Landmark Shape Predictor**: Facilitates landmark-based facial mapping.

---

## **Getting Started**

### **Prerequisites**
- Python 3.8+
- CUDA-compatible GPU (optional for faster processing)
- Dependencies: `torch`, `torchvision`, `numpy`, `opencv-python`, `dlib`

### **Run the Notebook**
Start using StyloMorph instantly by opening our pre-configured Colab notebook:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)]([LINK_TO_YOUR_COLAB_NOTEBOOK](https://colab.research.google.com/drive/1pXr8tnGr2tJlkkR5O0EukndqJD7_146Q?usp=sharing))

### **Steps to Use**
1. Open the Colab notebook using the link above.
2. Upload your source image and reference style image when prompted.
3. Run the cells to generate your stylized output.
4. Download the results directly from the notebook.

### **Notebook Features**
- **Interactive Interface**: Simple cell-based execution for ease of use.
- **Pre-Trained Models**: Automatically downloads StyleGAN2 and e4e models for effortless setup.
- **Customizable Options**: Adjust style intensity and other parameters to fine-tune results.
- **GPU Support**: Leverages Google Colab's free GPU for faster processing.

### **Example Outputs**

| Source Image | Style Reference | Stylized Output |
|--------------|-----------------|-----------------|
| ![Source Image](https://github.com/user-attachments/assets/14842cb9-4762-4398-b718-8208b3719a39) | ![Style Image](https://github.com/user-attachments/assets/58c95cf8-1706-4107-9bad-e497503144d4) | ![Stylized Output](https://github.com/user-attachments/assets/e7e2d3a4-8d37-4e36-b220-794ab0f37377) |

---

## **Applications**
- 🎨 Digital Art – Create stylized portraits with unique aesthetics.
- 📸 Content Creation – Generate artistic images for social media & branding.
- 🎭 Entertainment & Media – Enhance visuals with creative transformations.
- 📚 AI Research – Explore generative AI and style transfer techniques.

---

## **Future Scope**
- 🚀 Real-Time Video Stylization – Extend capabilities to video processing.
- 🖌 Full-Body Stylization – Expand beyond facial transformations.
- 🎨 AR/VR Integration – Enable immersive artistic experiences.
- 🛠 Interactive AI Tools – Develop user-friendly creative applications.

---

## **Acknowledgments**
- **StyleGAN2** and **e4e models** for their foundational contributions.
- **DLib** for robust facial landmark detection.
- The **FFHQ dataset** for providing diverse training data.

---

## Citation
If you use this work, please cite:

```
@INPROCEEDINGS{10866661,
  author={G., Uday Kiran and V., Srilakshmi and G., Padmini and B., Lavanya and A., Tejaswini and G., Vijay and D., Ranveer and B., Priyanka and H., Bhagya Laxmi},
  booktitle={2024 3rd Edition of IEEE Delhi Section Flagship Conference (DELCON)}, 
  title={One-Shot Stylization for Transformative Facial Art using StyloMorph}, 
  year={2024},
  volume={},
  number={},
  pages={1-8},
  keywords={Training;Shape;Computational modeling;Lighting;Streaming media;Media;Robustness;Real-time systems;Faces;Facial features;Face Stylization;pretrained models;Generative Adversarial Networks (GANs);Deep Learning},
  doi={10.1109/DELCON64804.2024.10866661}}
```

---

## Contact
For questions or collaborations, feel free to reach out:
- Name: Padmini Gudavalli
- [Gmail](pgudavalli2004@gmail.com)
- [LinkedIn](https://www.linkedin.com/in/padmini-gudavalli-226245259)
