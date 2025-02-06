# **StyloMorph**

**Transform Faces into Art with Precision and Simplicity**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pXr8tnGr2tJlkkR5O0EukndqJD7_146Q?usp=sharing)

## **Overview**

**StyloMorph** is a streamlined face stylization system designed to transform facial features into artistic styles while preserving unique characteristics. Powered by advanced models like **StyleGAN2** and **e4e**, StyloMorph ensures high-quality results with minimal computational requirements, making artistic transformations accessible to everyone.

### **Key Features**
- **Real-Time Stylization**: Achieve artistic transformations quickly and efficiently.
- **High Precision**: Retain essential facial details using DLib's facial landmark detection with 68 points.
- **Style Versatility**: Apply a wide range of artistic styles using StyleGAN2 and e4e models trained on the diverse FFHQ dataset.
- **User-Friendly**: Seamless integration with Google Colab for easy setup and usage.

---

## **How It Works**

StyloMorph uses a simple yet powerful pipeline for face stylization:

1. **Face Detection**: Maps facial features with 68 landmarks using **DLib Shape Predictor**.
2. **Latent Space Encoding**: Converts facial features to latent space using the **e4e encoder**.
3. **Style Application**: Applies artistic styles through **StyleGAN2** by manipulating latent space representations.
4. **High-Quality Outputs**: Produces stylized images that preserve the original identity while adopting the chosen style.

---

## **Architecture of StloMorph**

![image](https://github.com/user-attachments/assets/fbcac5d4-765a-4c0c-8723-84ec75a754ed)

---

## **Getting Started**

### **Run the Notebook**
Start using StyloMorph instantly by opening our pre-configured Colab notebook:

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)]([LINK_TO_YOUR_COLAB_NOTEBOOK](https://colab.research.google.com/drive/1pXr8tnGr2tJlkkR5O0EukndqJD7_146Q?usp=sharing))

### **Steps to Use**
1. Open the Colab notebook using the link above.
2. Upload your source image and reference style image when prompted.
3. Run the cells to generate your stylized output.
4. Download the results directly from the notebook.

---

## **Notebook Features**
- **Interactive Interface**: Simple cell-based execution for ease of use.
- **Pre-Trained Models**: Automatically downloads StyleGAN2 and e4e models for effortless setup.
- **Customizable Options**: Adjust style intensity and other parameters to fine-tune results.
- **GPU Support**: Leverages Google Colab's free GPU for faster processing.

---

## **Applications**

StyloMorph is perfect for:
- **Digital Artists**: Create personalized artistic portraits.
- **Content Creators**: Generate unique styles for social media and branding.
- **Media Professionals**: Enhance visuals with artistic transformations.

---

## **Example Outputs**

| Source Image | Style Reference | Stylized Output |
|--------------|-----------------|-----------------|
| ![Source Image](https://github.com/user-attachments/assets/14842cb9-4762-4398-b718-8208b3719a39) | ![Style Image](https://github.com/user-attachments/assets/58c95cf8-1706-4107-9bad-e497503144d4) | ![Stylized Output](https://github.com/user-attachments/assets/e7e2d3a4-8d37-4e36-b220-794ab0f37377) |

---

## **Acknowledgments**

- **StyleGAN2** and **e4e models** for their foundational contributions.
- **DLib** for robust facial landmark detection.
- The **FFHQ dataset** for providing diverse training data.

---

## **Contact**

For questions or support, please open an issue on GitHub or reach out via email at [pgudavalli2004@gmail.com](mailto:pgudavalli2004@gmail.com).
