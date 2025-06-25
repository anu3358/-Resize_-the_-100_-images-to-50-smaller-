# -Resize_-the_-100_-images-to-50-smaller-
PROJECT CATEGory
# 🖼️ Natural Image Preprocessing with OpenCV

A Colab-powered image preprocessing pipeline using the **Natural Images** dataset from Kaggle. This project focuses on filtering, organizing, and resizing images for use in computer vision and machine learning workflows.

---

## 📌 Highlights

- 🚀 **Runs directly in Google Colab** – no setup required  
- 🗂️ Downloads and extracts 100 sample images from multiple classes  
- ✂️ Efficiently resizes images using OpenCV (`cv2`)  
- 🧠 Great for building datasets for ML/CV models  

---

## 📂 Dataset Used

**Natural Images** from Kaggle:  
https://www.kaggle.com/datasets/prasunroy/natural-images

Categories include:
- Airplane ✈️
- Car 🚗
- Cat 🐱
- Dog 🐶
- Flower 🌸
- Fruit 🍎
- Horse 🐎
- Human 👤

---

## 🧰 Tech Stack

| Tool           | Purpose                        |
|----------------|--------------------------------|
| Google Colab   | Cloud execution                |
| OpenCV         | Image resizing & processing    |
| KaggleHub      | Simple dataset download        |
| Python (os, shutil) | File & folder management     |

---

## 🧪 How It Works

1. 🔗 **Install Dependencies**  
   OpenCV and KaggleHub are installed in Colab.

2. 📦 **Download Dataset**  
   Pulls images directly from the Kaggle dataset.

3. 🗃️ **Organize Files**  
   Copies and renames the first 100 images into a new directory.

4. 🖼️ **Resize Images**  
   Reduces image size by 90% using `cv2.resize()`.

---

## 📁 Folder Structure

📁 /content
│
├── images/ # 100 original images
└── resize_images/ # Resized (10% scale) images

yaml
Copy
Edit

---

## 🧷 Sample Output

Images are resized from original dimensions to thumbnails.

<p align="center">
  <img src="https://i.imgur.com/84uZbRk.png" width="500" alt="Sample resized images">
</p>

---

## ⚙️ Prerequisites

| Package       | Install Command               |
|---------------|-------------------------------|
| OpenCV        | `!pip install opencv-python`  |
| KaggleHub     | `!pip install kagglehub`      |

✅ Colab handles everything – no local environment needed.

---

## 👤 Author

**🧠 Mutnamerelevant**  
Passionate about deep learning, vision pipelines & automation  
🔗 GitHub: [mutnamerelevant](https://github.com/mutnamerelevant)

---

## 📄 License

This repository is licensed under the MIT License.  
Dataset © Kaggle contributors — used here for educational/demo purposes.

---

## 🌟 Show Your Support

If you found this useful, please ⭐️ the repo – it helps others find this project!

<p align="center">
  <a href="https://colab.research.google.com/"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a>
</p>
🔍 Need a Downloadable File?
