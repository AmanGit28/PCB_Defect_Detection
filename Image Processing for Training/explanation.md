# 🧩 Image Processed for Training

This folder shows how a large original PCB image was processed into smaller, same-sized patches for model training.

---

## 📸 Image Overview

<div align="center">

**Original Image (3034 × 1586)**  
<img src="./Original_Image.png" alt="Original PCB Image" style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;"/>

<br><br>⬇️⬇️⬇️<br><br>

**Processed Image (Each patch: 1011 × 528)**  
<img src="./processed_image.png" alt="Processed Patches" style="max-width: 100%; height: auto; border: 1px solid #ccc; border-radius: 8px;"/>

</div>

---

## 🧠 Explanation

- The **original image** was manually divided into smaller, equal-sized patches for consistent YOLO training input.  
- Each **processed image patch** is **1011 × 528 pixels** (W × H).  
- Uniform patch sizes help YOLO learn **localized PCB defects** more efficiently.  
- This example visually explains the preprocessing workflow used before model training.

---

## 🗂️ Folder Contents

