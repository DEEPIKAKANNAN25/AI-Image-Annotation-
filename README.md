# 🖼️ AI Image Annotation for Multi‑Class Scene Classification  

## 📌 Project Overview  
This project demonstrates the complete workflow of creating a high‑quality image annotation dataset for a computer vision classification task. Using **Label Studio**, I manually annotated **120 scene images** into six predefined categories to create ground‑truth data suitable for machine learning model training and evaluation.  

The project was completed to gain practical experience in **image annotation**, **dataset preparation**, **quality assurance**, and **annotation workflows** similar to those used in AI and Machine Learning Data Operations.  

---

## 🎯 Objective  
The objective of this project is to create a clean and accurately annotated dataset by manually labeling scene images into predefined categories while maintaining consistency and annotation quality.  

---
## ✨ Features

- Manual annotation of 120 scene images
- Six predefined scene categories
- Single-label image classification
- Ground-truth dataset creation
- Quality assurance and annotation verification
- Dataset organization using Python

## 📂 Dataset Information  
- 📦 **Dataset Name**: Intel Image Classification Dataset
-  📚 **Source**: Intel Image Classification Dataset (Kaggle)
- 🖼️ **Total Images**: 120  
- 🏷️ **Classes**:  
  - 🏢 Building  
  - 🌲 Forest  
  - 🧊 Glacier  
  - ⛰️ Mountain  
  - 🌊 Sea  
  - 🛣️ Street  
- 📝 **Annotation Type**: Single‑label Image Classification
  

---

## 🛠️ Tools Used  
- 🖊️ Label Studio 1.20.0  
- 🐍 Python 3.13  
- 💻 Visual Studio Code  
- 🔧 Git  
- 🌐 GitHub  

---
## ⚙️ Requirements

- Python 3.13
- Label Studio 1.20.0
- Git
 ---

## 🔄 Project Workflow  
1. 📥 Downloaded the Intel Image Classification Dataset  
2. 🗂️ Selected 120 images for annotation  
3. 🏗️ Created a new Label Studio project  
4. ⚙️ Configured the labeling interface with six scene categories  
5. 📸 Imported the images into Label Studio  
6. ✍️ Manually annotated each image  
7. 🔍 Verified annotations for consistency and correctness  
8. 📤 Exported the annotations in JSON and CSV formats  
9. 🐍 Used Python to generate a structured professional dataset file  

---

## 🏷️ Label Categories  

| 🏷️ Label   | 📖 Description |
|------------|----------------|
| 🏢 Building | Images primarily containing buildings or man‑made structures |
| 🌲 Forest   | Images dominated by trees and dense vegetation |
| 🧊 Glacier  | Snow or ice‑covered landscapes |
| ⛰️ Mountain | Rocky mountains or hills without dominant glacier coverage |
| 🌊 Sea      | Oceans, beaches, or large water bodies |
| 🛣️ Street   | Roads, highways, or urban street scenes |

---
## 📁 Folder Structure

```text
AI-Image-Annotation-Project/
│
├── Dataset/
├── Documentation/
├── Exports/
├── Python/
│   └── create_professional_dataset.py
├── Screenshots/
├── README.md
└── requirements.txt
```

---
## 🐍 Python Usage

Python was used to organize the annotated dataset and generate a structured CSV file for documentation and analysis.

The script:

- Reads the dataset folders
- Assigns unique image IDs
- Extracts image names
- Records scene labels
- Stores annotator information
- Adds QA verification status
- Generates a professional CSV dataset for documentation
---

## 🔍 Quality Assurance  
To improve annotation quality:  
- 👀 Each image was manually reviewed  
- 🏷️ Only one label was assigned per image  
- 📖 Category definitions were followed consistently  
- ⚖️ Ambiguous images were carefully inspected before labeling  
- 📑 The exported annotations were verified before documentation  

---

## 🎉 Project Outcome  
Successfully created a manually annotated image dataset containing **120 scene images across six classes** using Label Studio.  

The project demonstrates practical experience in:  
- 🖊️ Image Annotation  
- 📂 Dataset Preparation  
- 🏷️ Ground Truth Creation  
- ✅ Quality Assurance  
- 🔄 Annotation Workflow  
- 🐍 Dataset Organization using Python  

---

## 💡 Skills Demonstrated  
- 🖊️ Image Annotation  
- 👁️ Computer Vision Dataset Preparation  
- 🏗️ Label Studio  
- 🐍 Python  
- ✅ Data Quality Assurance  
- 📂 Dataset Management  
- 📑 Documentation  
- 🔧 Git & 🌐 GitHub  

---

## 🚀 Future Improvements

- Expand the dataset with additional scene images.
- Introduce multi-annotator validation.
- Measure inter-annotator agreement.
- Train and evaluate an image classification model.

---


