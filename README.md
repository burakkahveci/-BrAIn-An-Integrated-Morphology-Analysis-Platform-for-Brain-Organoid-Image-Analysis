# 🧠 BrAIn: An Integrated Platform for Brain Organoid Image Analysis

Classification • Segmentation • Object Detection – No Code GUI for 2D Organoid Morphology

### 📌 Overview

BrAIn is the first open-source tool to unify classification, segmentation, and detection tasks for brain organoid imaging. Designed to support both research and diagnostic workflows, BrAIn empowers users with:
	•	💡 Multi-task analysis from a single interface
	•	🖼️ Morphological feature extraction: budding, folds, neuroectodermal structures
	•	🧪 Tested on both synthetic and real datasets
	•	🖱️ No-code GUI for users with no programming background


### ✨ Key Features

| Feature                             | BrAIn | Other Tools (e.g., CellProfiler, Ilastik) |
|-------------------------------------|:-----:|:-----------------------------------------:|
| Classification                     | ✅    | ❌ / Limited                              |
| Segmentation                       | ✅    | ✅                                        |
| Object Detection                   | ✅    | ❌                                        |
| Brain Organoid Specific            | ✅    | ❌                                        |
| GUI (No Code Required)             | ✅    | ✅ / Limited                              |
| Manual Mask Editing                | ✅    | ❌ / Limited                              |
| Platform Compatibility (Mac/Win)  | ✅    | ⚠️ Varies                                 |
| Model Import / Export              | ✅    | ❌                                        |


### 📷 Sample UI Screenshots


<img width="550" alt="image" src="https://github.com/user-attachments/assets/049bf461-9014-45ea-bdfa-970702e49726" />


### 🚀 Installation

<pre lang="markdown">
```
# Create and activate conda environment
conda create -n brain python=3.9
conda activate brain

# Clone the repo
git clone https://github.com/yourusername/BrAIn.git
cd BrAIn

# Install requirements
pip install -r requirements.txt
```
</pre>

### 🧑‍💻 Usage

<pre lang="markdown">
```
python BrAIn_UI.py
	
```
</pre>

From the GUI:
	1.	Select input image or directory
	2.	Choose the task: Classification, Segmentation, or Detection
	3.	Click “Start” to process and view results
	4.	Optionally, review or manually edit segmentations

### 📒 Citation

If you use BrAIn in your work, please cite:

Kahveci B., et al. BrAIn: A comprehensive artificial intelligence-based morphology analysis system for brain organoids and neuroscience. (2025)

### 🤝 Contributing

We welcome contributions! You can:

* Submit a pull request
* Report bugs or feature requests under Issues
* Suggest model integrations or UI improvements

 
### 🧠 Acknowledgements

* Developed by Burak Kahveci
* Supervised by Sinan GUven & Yalın Bastanlar
* Supported by ADEP - DEU (TSA 2023-3026 project) & EuroHPC (EHPC-BEN-2023B03-002)
