# 🌍 **SVAMITVA**  

## 📌 **Overview**  
SVAMITVA is a **deep learning-based** computer vision project designed to detect and analyze **lakes** 🏞️ and **roofs** 🏠 from satellite imagery. The project integrates two datasets from **Roboflow**, merges them, and trains a detection model to classify these features effectively.  

## 📂 **Dataset**  
- **Sources**:  
  - 🏞️ [Lakes Dataset (Roboflow)](https://universe.roboflow.com/hackshit/satellite-images-xl3af)  
  - 🏠 [Roofs Dataset (Roboflow)](https://universe.roboflow.com/fyp-scksi/building-detection-from-satellite-images-ghtvy)  
- **Merging Process**:  
  - 🛠️ Both datasets were **combined** and preprocessed for consistency.  
  - 🏗️ Augmentation techniques were applied to improve model generalization.  

⚠️ **Reminder:** 📝 Update the **class names** and **counts** in the **YAML file** before training to ensure correct class mappings.  

## 🛠️ **Installation**  
To set up and run this project, follow these steps:  

```bash
git clone https://github.com/your-username/SVAMITVA.git  
cd SVAMITVA  
pip install -r requirements.txt
```

## 🚀 **Usage**  
1. **Open the Jupyter Notebook 🖼️:** 
   - Run `SVAMITVA.ipynb` using Jupyter Notebook or Google Colab.  

2. **Follow the Steps in the Notebook ✅:**  
   - The notebook contains **data preprocessing, model training, and inference steps**.  
   - Run the cells sequentially to train and evaluate the model.  

3. **Perform Inference 🖼️:**  
   - Upload test images in the notebook and execute the provided inference cells.  

## 🔬 **Model Details**  
- **Backbone Model**: YOLOv8⚡
- **Framework**: PyTorch 🧠 
- **Performance Metrics**: 📊Precision - 84.49%, 🏆mAP@50 - 0.8964  

## 📈**Results**  
- ✔️Achieves high accuracy in detecting and classifying **lakes and roofs**.  
- ✔️Robust against variations in image quality and environmental conditions.  

## 🤝 **Contributing**  
If you’d like to contribute, feel free to fork the repository and submit a pull request🔄!  

## 📜**License**  
This project is licensed under the MIT License.📝
    
