# 📊 Defect Detection Model

A machine learning project designed to automate the visual inspection of metal nuts, a common component in industrial manufacturing.

## 🧠 Overview

In a typical manufacturing setting, workers manually inspect parts—in this case, metal nuts, small threaded components used to fasten machinery. Each nut is labeled as either **defective** or **correct** based on human judgment.

In this project, I used a dataset of labeled images—each showing a metal nut classified as either defective or correctly manufactured—to train a machine learning model that automates this visual inspection. By replicating the human judgment process, this approach has the potential to reduce manual labor, improve inspection accuracy, and minimize inconsistencies in quality control.

## 🛠️ Tools & Technologies

- **Languages**: Python  
- **Libraries**: scikit-learn, OpenCV, NumPy, Matplotlib  
- **Environment**: Jupyter Notebook

## 🔍 Techniques Used

- Image preprocessing (grayscale conversion, resizing,filtering)  
- Feature extraction  
- Binary classification of labeled images 
- Model evaluation with confusion matrices and accuracy metrics

## 📂 Dataset

- **Component**: Metal nuts used in industrial fastening  
- **Source**: https://www.mvtec.com/company/research/datasets/mvtec-ad/downloads
- **Format**: Image files labeled as defective or correct  
- **Note**: Full dataset not included due to licensing. A sample is available in `/data`.

## 📈 Results

Two confusion matrices are included to compare model performance:
- **Baseline Model**: Initial results using default parameters  
- **Tuned Model**: Improved accuracy after parameter optimization and feature selection

## 🚧 Status

Currently refining model performance and designing a dashboard to visualize predictions and inspection metrics.

## 📌 Future Enhancements

- Interactive dashboard using Streamlit or Dash  
- Integration with live camera feed for real-time defect detection  
- Deployment via web app or API

## 🤝 Contributions

Open to feedback, suggestions, and collaboration. Feel free to fork, submit issues, or reach out with ideas for improving the model or expanding its applications.