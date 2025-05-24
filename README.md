# Thyroid Cancer Recurrence Prediction

## Overview 📝

This project focuses on predicting the recurrence of thyroid cancer in patients after initial treatment. The goal is to build a machine learning system that can identify patients at higher risk of relapse using their clinical data.

## Dataset 💾

The dataset used for this project contains comprehensive patient information related to thyroid cancer diagnoses and follow-ups. Key features include:

-   Age at diagnosis/treatment
-   Gender
-   Smoking history
-   History of radiotherapy
-   Thyroid function status
-   Physical examination findings
-   Presence of enlarged lymph nodes (Adenopathy)
-   Pathology type of the thyroid cancer
-   Focality (unifocal or multifocal cancer)
-   Risk category of the cancer
-   T, N, M, and Stage classifications
-   Response to initial treatment
-   **Target Variable**: `Recurred` (indicating if the cancer recurred)

The dataset file is `thyroid_cancer.csv`.

## Files 📂

-   `thyroid_cancer.csv`: The dataset containing patient information.
-   `thyroid_cancer.ipynb`: Jupyter Notebook containing the code for data analysis, model training, and evaluation 💻.
-   `Thyroid Cancer Detection.pdf`: A document providing an overview of the project 📄.
-   `Thyroid_cancer_detection.pptx`: Presentation slides summarizing the project 📊.

## Dependencies ⚙️

-   pandas
-   numpy
-   matplotlib
-   seaborn
-   scikit-learn

Install them using:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Data Preprocessing 🛠️

The data preprocessing steps included:

* Handling missing values by dropping rows with critical missing values and imputing minor numerical features with the mean (as mentioned in `Thyroid_cancer_detection.pptx`).
* Converting categorical features to numerical format using Label Encoding and One-Hot Encoding (as mentioned in `Thyroid_cancer_detection.pptx`).

## Exploratory Data Analysis (EDA) 🔍

To understand the data:

* Visualizations including pair plots, histograms, class distributions, and box plots were used (evident from `thyroid_cancer.ipynb` and slide 14 of `Thyroid_cancer_detection.pptx`).
* A correlation heatmap was generated to identify relationships between features (as seen in slide 19 of `Thyroid_cancer_detection.pptx`).

## Model Selection and Training 🧠

* **Model**: Random Forest Classifier 🌳 (as stated in `thyroid_cancer.ipynb` and slide 21 of `Thyroid_cancer_detection.pptx`).
* The Random Forest model was chosen for its ability to handle both categorical and numerical features, robustness to outliers, and effectiveness with imbalanced datasets (reasons mentioned in slide 22 of `Thyroid_cancer_detection.pptx`).

## Model Evaluation ✅

Model performance was evaluated using metrics such as:

* Classification Report (as seen in slide 2 of `Thyroid_cancer_detection.pptx`).
* Confusion Matrix (as seen in slide 3 of `Thyroid_cancer_detection.pptx`).
* ROC Curve (as seen in slide 6 of `Thyroid_cancer_detection.pptx`).
* Feature Importance was also analyzed (as seen in slide 5 of `Thyroid_cancer_detection.pptx`).

## Results ✨

The project aimed to build a model to predict thyroid cancer recurrence. The results of the model evaluation are detailed in the notebook (`thyroid_cancer.ipynb`) and the presentation (`Thyroid_cancer_detection.pptx`).

## Setup ⚙️

1.  Clone the repository ⬇️.
2.  Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn
    ```
3.  Run the notebook:
    ```bash
    jupyter notebook thyroid_cancer.ipynb
    ```

## Usage ▶️

The `thyroid_cancer.ipynb` notebook can be used to:

* Explore the dataset.
* Preprocess the data.
* Train the Random Forest Classifier model.
* Evaluate the model's performance.

## Contributing 🤝

Contributions to this project are welcome! If you have ideas for improvements or find any issues, please feel free to submit a pull request 🚀.

## License 📄

This project is open source and available under the MIT License.
