# LEAVES DISEASE DETECTION

This Project aims to Develop a Deep Learning Model with Tensorflow to Classify Leaves as Diseased or Not.

This Work was Undertaken as Part of a Machine Learning Projects for a College Course

The Repository includes a Jupyter Notebook that Implements Advanced Data Preprocessing, Exploratory Data Analysis (EDA), Mdoel Training and Evaluation

## DATASET

A Publicly Available Dataset was used for Training and Testing. The Dataset contains Two Directory, 'train' and 'test' containing Images for Training and Testing purposes, respectively.

### DIRECTORY STRUCTURE

**Checkpoint/Checkpoint.weights.h5** - The Directory to store Trained Model<br>
**Dataset/train & Dataset/test** - The Dataset leveraged for Empirical Assessment<br>
**Notebook.ipynb** - The Primary Notebook containing the Actual Code

### DEPENDENCIES

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow
```

---

## MODEL DETAILS

**Model Training** <br>
This Sequential Model contains 9 Layers aside of Input and Output, which includes
- **DataAugmentation Layer** <br>
  Image Transformation like Flipping, Rotation and Zooming to Increase Dataset
- **Conv2D Layer** <br>
  Extracts Spatial Features from Image using Learnable Filters to Detect Pattern
- **Max_Pooling2D Layer** <br>
  Reducing Spatial Dimension by Selecting the Maximum Value in a Region
- **Global_Average_Pooling2D Layer** <br>
  Condenses Each Feature Map into a Single Value by Averaging, Reducing Parameters

**Result** <br>
The Resulted Accuracy obtained is
- Accuracy : 90.32% | Validation Accuracy : 85% 
- Loss : 28.28% | Validation Accuracy : 58.97%

The Overall Accuracy is 86.65% [Sufficient considering Dataset size] with loss around 42.93% [Need Improvement & Fine Tuning].

---

## GETTING STARTED

**Clone the Repository** <br>
  Clone the Repository to your Local Machine
  ```bash
  git clone https://github.com/AakashAP/.git
  ```

**Open in Code Editor** <br>
  Navigate to the Project Folder and Open it in Jupyter Notebook and Execute in Sequential Order