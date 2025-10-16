# Image Processed for Training

This folder shows how the large original PCB image was processed into smaller, uniformly sized patches before training.

---

## 🖼️ Image Format Overview

| Original Image | → | Processed Image |
|----------------|---|-----------------|
| ![Original Image](Original_Image.png) | ➡️ | ![Processed Image](processed_image.png) |

---

### 📌 Description

- **Original Image Size:** 3034 × 1586  
  The full PCB image prepared manually before preprocessing.

- **Processed Images Size:** 1011 × 528  
  The original image is divided into multiple smaller patches of equal size.  
  These patches were generated manually, and each patch represents a specific region of the PCB.

---

### ⚙️ Purpose of Processing

Splitting the large PCB image into smaller patches helps in:
- Maintaining **uniform input sizes** for YOLO training  
- Allowing the model to **focus on localized defects**  
- Reducing memory usage and improving **training efficiency**

---

### 📁 Folder Layout

