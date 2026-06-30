# 🖼️ Image Caption Similarity using Sentence Transformers

## 📌 Overview

This project demonstrates how to compare an image with multiple text descriptions using the **Sentence Transformers CLIP model**. The notebook converts both images and text into vector embeddings and calculates **cosine similarity** to determine which caption best matches the given image.

It is a simple introduction to **multimodal AI**, where visual and textual data are represented in the same embedding space for similarity comparison.

---

## 🚀 Features

* Load and preprocess images.
* Generate image embeddings using a pre-trained CLIP model.
* Encode multiple text descriptions into embeddings.
* Compute cosine similarity between image and text embeddings.
* Identify and display the most relevant caption.
* Demonstrates image-text retrieval using deep learning.

---

## 🛠️ Technologies Used

* Python
* Google Colab
* Sentence Transformers
* CLIP Model
* PIL (Python Imaging Library)
* NumPy
* Scikit-learn (Cosine Similarity)

---

## 📂 Project Workflow

1. Import the required libraries.
2. Load a pre-trained Sentence Transformers CLIP model.
3. Read the input image.
4. Define a list of candidate text descriptions.
5. Generate embeddings for both the image and the text.
6. Calculate cosine similarity scores.
7. Select and display the caption with the highest similarity score.

---

## 📊 Output

The notebook outputs:

* Similarity score for each text description.
* The best matching caption for the input image.

---

## 🎯 Learning Objectives

This project helps understand:

* Multimodal embeddings
* Image-text similarity
* CLIP models
* Sentence Transformers
* Cosine similarity
* Basic image retrieval concepts

---

## 📁 Repository Structure

```text
ImageCapturing.ipynb
README.md
```

---

## ▶️ How to Run

1. Clone this repository.
2. Install the required libraries.
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Upload an image.
5. Run all cells to compare the image with the provided text descriptions.

---
