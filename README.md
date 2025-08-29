# Landmark Classification & Tagging with CNN

This project is part of the **Udacity AWS Machine Learning Fundamentals Nanodegree**.  
The goal is to build a **Convolutional Neural Network (CNN)** that can classify landmarks and tag them for social media applications.  

---

## 📌 Project Overview
In this project, I implemented a pipeline for **landmark image classification** using both a **custom CNN** and **transfer learning**. The workflow covers:
- Data loading and preprocessing
- Data augmentation for better generalization
- Designing and training a custom CNN architecture
- Fine-tuning with a pre-trained network
- Model evaluation and comparison against benchmarks  

---

## 📂 Dataset
The dataset consists of landmark images used for training and testing classification models.  
(*Note: Dataset not included in this repo. Please refer to Udacity’s project instructions or use your own dataset.*)

---

## ⚙️ Approach
1. **Data Preprocessing**  
   - Normalization, resizing, and augmentation (rotation, flips, etc.)  

2. **Model Architectures**  
   - **Custom CNN**: Designed and trained from scratch.  
   - **Transfer Learning**: Leveraged a pre-trained model for higher accuracy.  

3. **Training**  
   - Optimized with Adam optimizer, cross-entropy loss.  
   - Early stopping and validation tracking used.  

4. **Evaluation**  
   - Both models surpassed benchmark accuracy.  
   - Custom CNN achieved excellent performance, with transfer learning performing even better.  

---

## 📊 Results
- **Custom CNN**: Surpassed benchmark accuracy with strong generalization.  
- **Transfer Learning Model**: Outperformed baseline significantly.  
- Reviewer feedback highlighted the clean code, strong architecture design, and flawless pipeline implementation 🚀  

---

## 🛠️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/landmark-classification-cnn.git
   cd landmark-classification-cnn
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
3. Run Jupyter Notebook or training scripts:
   ```bash
   jupyter notebook

🙏 Acknowledgments

Udacity for providing the project and guidance.

Dataset providers for making image classification research possible.











