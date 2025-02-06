# **StyloMorph**

**Transform Faces into Art with Precision and Simplicity**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1pXr8tnGr2tJlkkR5O0EukndqJD7_146Q?usp=sharing)

## **Overview**

**StyloMorph** is a streamlined face stylization system designed to transform facial features into artistic styles while preserving unique characteristics. Powered by advanced models like **StyleGAN2** and **e4e**, StyloMorph ensures high-quality results with minimal computational requirements, making artistic transformations accessible to everyone.

### **Key Features**
✅ **One-Shot Stylization**: Transforms faces with just a single reference style image.  
✅ **High-Quality Outputs**: Maintains facial details while applying stylized transformations.  
✅ **Efficient Processing**: Uses **e4e encoding** for optimized GAN inversion, reducing computation time.  
✅ **Real-Time Stylization**: Works efficiently even on resource-limited hardware.  
✅ **Customizable Style Intensity**: Fine-tune outputs with adjustable parameters.  
✅ **Supports Multi-Shot Stylization**: Extends capabilities to multiple reference styles. 
✅ **User-Friendly**: Seamless integration with Google Colab for easy setup and usage.

---

## **How It Works**

### **Architecture of StloMorph**

![image](https://github.com/user-attachments/assets/4e255708-005a-48f1-b9f2-ecc2bb87f6cd)

StyloMorph uses a simple yet powerful pipeline for face stylization:

1. **Facial Feature Extraction**: Uses **DLib Shape Predictor** (68 facial landmarks) to detect key facial features.

![image](https://github.com/user-attachments/assets/1ab86021-420d-4caf-89ad-1a9256cd8201) 

2. **Latent Space Encoding**: Maps facial features into **StyleGAN2’s latent space** using the **e4e encoder**.

![image](https://github.com/user-attachments/assets/6918adc3-23c2-444f-898f-54d6ceab1ae0)

3. **Style Transfer**: Applies artistic transformations while preserving facial identity.

![image](https://github.com/user-attachments/assets/6f30748b-625f-4378-8b9a-05435283f608)

 4. **Output Generation**: Generates realistic, high-resolution stylized images.

![image](https://github.com/user-attachments/assets/c616e77e-6504-422c-8155-8e2c8f8bbe4b)


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
🎨 Digital Art – Create stylized portraits with unique aesthetics.
📸 Content Creation – Generate artistic images for social media & branding.
🎭 Entertainment & Media – Enhance visuals with creative transformations.
📚 AI Research – Explore generative AI and style transfer techniques.

---

## **Future Scope**
🚀 Real-Time Video Stylization – Extend capabilities to video processing.
🖌 Full-Body Stylization – Expand beyond facial transformations.
🎨 AR/VR Integration – Enable immersive artistic experiences.
🛠 Interactive AI Tools – Develop user-friendly creative applications.

---

## **Acknowledgments**

- **StyleGAN2** and **e4e models** for their foundational contributions.
- **DLib** for robust facial landmark detection.
- The **FFHQ dataset** for providing diverse training data.

---

## **Contact**

For questions or support, please open an issue on GitHub or reach out via email at [pgudavalli2004@gmail.com](mailto:pgudavalli2004@gmail.com).
