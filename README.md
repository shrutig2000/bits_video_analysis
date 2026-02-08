# 📘 Video Analysis Assignment – M.Tech (AI/ML)

## 🧑‍🎓 Student Details
- **Name:** G Shruti  
- **Program:** M.Tech (Artificial Intelligence & Machine Learning)  
- **Institution:** BITS Pilani  
- **Course:** Video Analysis  
- **BITS_ID** `2024ac05668`


---

## 📌 Assignment Overview

This repository contains the complete implementation, analysis, and
documentation for the **Video Analysis course assignment**. The work focuses
on understanding and comparing **classical computer vision techniques** and
**deep learning–based approaches** for video classification using Python.

The assignment emphasizes:
- Conceptual clarity  
- Practical implementation  
- Experimental evaluation  
- Clear documentation of results  

---

## 🧠 Topics Covered

The notebooks in this repository explore concepts such as:

- Video frame extraction and preprocessing  
- Temporal information analysis  
- Motion estimation and understanding  
- Feature extraction from video sequences  
- Classical machine learning approaches for video classification  
- Deep learning approaches using CNNs  
- Comparative performance analysis  

(Detailed explanations are provided inside individual notebooks and the final
report.)

---

## 📂 Repository Structure

```text
bits_video_analysis/
│
├── part_a_classical.ipynb        # Classical video classification
├── part_b_deep_learning.ipynb    # Deep learning–based video classification
├── comparative_analysis.ipynb    # Comparative analysis
│
├── reports/
│   ├── part_a_classical.pdf
│   ├── part_b_deep_learning.pdf
│   ├── comparative_analysis.pdf
│   └── Student_Comparative_report.pdf
│
├── dataset_info/
│   ├── dataset_url.txt
│   ├── dataset_description.md
│   ├── data_statistics.txt
├── results/
│   ├── confusion_matrices/       # Confusion matrix images
│   ├── performance_plots/        # Accuracy and ROC plots
│   └── feature_visualizations/   # LBP, motion, and feature examples
│
│
├── requirements.txt              # Python dependencies
└── README.md
```
----------------------------------
## ⚙️ Technologies & Tools Used

- Python
- Jupyter Notebook
- OpenCV
- NumPy
- scikit-learn
- scikit-image
- PyTorch
- Matplotlib

All dependencies are listed in `requirements.txt` for reproducibility.

2. Navigate to the project directory
cd bits_video_analysis

3. Install dependencies
pip install -r requirements.txt

4. Launch Jupyter Notebook
jupyter notebook

5. Run notebooks in the following order

part_a_classical.ipynb

part_b_deep_learning.ipynb

comparative_analysis.ipynb

**📊 Results & Observations**

Classical machine learning models demonstrated strong performance under
limited data conditions.

Deep learning models showed potential for spatiotemporal representation
learning but were constrained by dataset size and training duration.

Performance plots, confusion matrices, and feature visualizations are
available in the results/ directory.

A detailed comparative discussion, including performance metrics,
confusion matrices, ROC analysis, and error analysis, is provided in the
final report.

**📝 Notes**

This repository is intended strictly for academic and educational purposes.

The HMDB51 dataset was obtained via a Kaggle mirror; the full dataset is
not included due to size constraints.

Only dataset metadata, sample frames, and result visualizations are
provided.

Experimental results may vary depending on system configuration and
library versions.

**📎 References**

HMDB51 Dataset (Kaggle mirror)

Course lecture materials (Video Analysis – BITS Pilani)

Standard computer vision and video analysis literature

OpenCV, scikit-learn, scikit-image, and PyTorch documentation




