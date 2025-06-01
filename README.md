# 🧠 BrAIn: An Integrated Platform for Brain Organoid Image Analysis

* Classification
* Segmentation
* Object Detection
  
***No Code GUI for Organoid Morphology Analysis***

### 📌 Overview

BrAIn is the first open-source tool to unify classification, segmentation, and detection tasks for brain organoid imaging. Designed to support both research and diagnostic workflows, BrAIn empowers users with:

* 💡 Multi-task analysis from a single interface
* 🖼️ Morphological feature extraction: budding, folds, neuroectodermal structures
* 🧪 Tested on both synthetic and real datasets
* 🖱️ No-code GUI for users with no programming background


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


<img width="550" alt="image" src="[(https://github.com/burakkahveci/-BrAIn-An-Integrated-Morphology-Analysis-Platform-for-Brain-Organoid-Image-Analysis/blob/main/Picture1.png?raw=true)]" />


### 🚀 Installation

<pre lang="markdown">
```
# Create and activate conda environment
conda create -n brain python=3.9
conda activate brain

# Clone the repo
git clone https://github.com/burakkahveci/-BrAIn-An-Integrated-Morphology-Analysis-Platform-for-Brain-Organoid-Image-Analysis.git
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

* **Datasets:**
[Datasets Link](https://zenodo.org/records/15503283?token=eyJhbGciOiJIUzUxMiIsImlhdCI6MTc0ODA5MzM2OCwiZXhwIjoxNzU5MDE3NTk5fQ.eyJpZCI6ImYzMzM2ZDI2LTVjNjktNDk2Yy04YzY5LWQwODViMjgwMWNlNyIsImRhdGEiOnt9LCJyYW5kb20iOiI0ZGQwZTY2NGQ3ODU4OTQ5ZjJhMTA5ZjcwZDE0MjMzYiJ9.3DR3CqZN1GgFf1pPGgjvob4B52mDWO4RW-JZk_7Yk2-qN4Zln9dVTN7yEN_6o_Zt4JsVAykiTmKTGAKU-Pkc6w).

### 🤝 Contributing

We welcome contributions! You can:

* Submit a pull request
* Report bugs or feature requests under Issues
* Suggest model integrations or UI improvements

 
### 🧠 Acknowledgements

* Developed by Burak Kahveci
* Supported by ADEP - DEU (TSA 2023-3026 project) & EuroHPC (EHPC-BEN-2023B03-002)
