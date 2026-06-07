# 🦴 Skeletal Variation: Comparative Analysis of Human, Mammal, and Bird Skeletons

> Academic project developed during the **Data Science Essentials with Python** course from the Cisco Networking Academy.

## 📖 Overview

This project explores skeletal variation across different species through the analysis of biological datasets containing information about human bones, mammalian cervical vertebrae, and bird cervical vertebrae.

Using Python and data analysis techniques, the project investigates anatomical patterns, skeletal development, and evolutionary constraints that shape vertebrate skeletons.

The analyses combine exploratory data analysis, descriptive statistics, and visualization techniques to better understand similarities and differences among species.

---

## 🎯 Objectives

* Explore the anatomical organization of the human skeleton.
* Investigate bone fusion throughout human development.
* Analyze the distribution of bones across body regions.
* Study cervical vertebrae variation in mammals.
* Examine neck vertebrae diversity among birds.
* Identify biological and evolutionary patterns through data analysis.

---

## 📊 Datasets

### Adult Human Skeleton Dataset

Dataset containing information about bones in the adult human skeleton.

**Attributes:**

| Column     | Description                                    |
| ---------- | ---------------------------------------------- |
| name       | Bone name                                      |
| region     | Anatomical region                              |
| subregion  | Anatomical subdivision                         |
| side       | Left, right, or center                         |
| fused_from | Number of bones fused into the adult structure |

### Mammal Neck Bones Dataset

Dataset containing the number of cervical vertebrae across different mammalian species.

**Attributes:**

| Column         | Description                  |
| -------------- | ---------------------------- |
| species        | Mammal species               |
| neck_vertebrae | Number of cervical vertebrae |

### Bird Neck Bones Dataset

Dataset containing cervical vertebrae counts for various bird species.

**Attributes:**

| Column         | Description                  |
| -------------- | ---------------------------- |
| species        | Bird species                 |
| neck_vertebrae | Number of cervical vertebrae |

---

## 🔬 Analyses Performed

### Human Skeletal Structure

The project investigates:

* Distribution of bones by anatomical region;
* Human skeletal organization;
* Bone counts across body structures;
* Developmental fusion of bones.

### Bone Distribution in Hands and Feet

One of the analyses evaluates the well-known biological observation that more than half of the bones in the human body are located in the hands and feet.

The study confirms this anatomical characteristic through direct analysis of the dataset.

### Bone Fusion During Development

The project estimates the difference between infant and adult skeletons by analyzing bones formed through fusion.

This analysis illustrates how skeletal development reduces the number of bones throughout growth.

---

## 🦒 Mammalian Neck Vertebrae Analysis

The mammal dataset is used to explore one of the most interesting patterns in vertebrate evolution.

### Main Findings

* Most mammals possess exactly seven cervical vertebrae.
* This pattern remains highly conserved regardless of neck length.
* Species such as giraffes still maintain seven cervical vertebrae despite their elongated necks.

### Evolutionary Exceptions

The analysis highlights species that deviate from the common mammalian pattern, demonstrating rare evolutionary adaptations.

---

## 🦢 Bird Neck Vertebrae Analysis

Unlike mammals, birds display substantial variation in cervical vertebrae counts.

### Investigations

* Frequency distributions;
* Most common vertebrae counts;
* Species with extreme values;
* Comparative anatomical variability.

### Findings

* Birds exhibit significantly greater cervical variation than mammals.
* Different species possess highly specialized neck structures adapted to feeding, locomotion, and environmental conditions.

---

## 📈 Data Science Techniques Applied

The project applies several fundamental data science techniques, including:

* Data Loading and Preparation
* Data Cleaning
* Exploratory Data Analysis (EDA)
* Filtering and Querying
* Statistical Summaries
* Grouping and Aggregation
* Frequency Analysis
* Data Visualization

---

## 🛠 Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Jupyter Notebook

---

## 🚀 How to Run

### Install Dependencies

```bash
pip install pandas numpy matplotlib
```

### Launch Jupyter Notebook

```bash
jupyter notebook
```

### Open the Project

```text
skeletal-variation.ipynb
```

Execute all notebook cells to reproduce the analyses and visualizations.

---

## 📚 Concepts Covered

* Data Science Fundamentals
* Exploratory Data Analysis (EDA)
* Data Visualization
* Comparative Anatomy
* Evolutionary Biology
* Statistical Analysis
* Biological Data Exploration
* Scientific Computing with Python

---

## 🌎 Real-World Relevance

Understanding skeletal variation has applications in:

* Evolutionary Biology
* Comparative Anatomy
* Paleontology
* Zoology
* Biological Research
* Science Education

The project demonstrates how data science techniques can be applied to biological datasets to uncover meaningful scientific insights.

---

## 🎓 Academic Context

This project was developed as part of the **Data Science Essentials with Python** course offered by the Cisco Networking Academy.

The course focuses on the practical application of Python for data analysis, visualization, and exploratory investigations using real-world datasets.

Through this project, concepts such as data manipulation, statistical reasoning, and scientific analysis are applied to biological datasets, demonstrating the interdisciplinary nature of modern Data Science.

---

## 📜 Course Information

**Course:** Data Science Essentials with Python

**Institution:** Cisco Networking Academy

### Topics Covered

* Python Programming
* Data Analysis
* Data Visualization
* Exploratory Data Analysis
* Statistics for Data Science
* Real-World Data Exploration

---

## 👨‍💻 Author

**Tamyres Silva**

Academic project developed as part of the Cisco Networking Academy's Data Science Essentials with Python program, applying data science techniques to biological and anatomical datasets.
