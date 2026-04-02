<div align="center">
  
# 📊 Exploratory Data Analysis (EDA) - P4AI-DS

**Assignment 1 | Programming for AI and Data Science (CO3135)** *Ho Chi Minh City University of Technology (HCMUT)*

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

</div>

---

## 👥 Team: Ben 10
| Name | Student ID | Class | Contribution |
| :--- | :--- | :--- | :--- |
| **Trần Phan Đăng Khôi** | 2352626 | CC03 | 50% |
| **Trương Anh Phan** | 2352881 | CC03 | 50% |

**Instructor:** Dr. Thanh-Sach LE  
**Semester:** I (Academic Year 2025-2026)

---

## 🚀 Project Overview
This repository contains the source code and report for Assignment 1 of the P4AI-DS course. The primary objective is to perform comprehensive **Exploratory Data Analysis (EDA)** across three different data modalities to prepare for downstream Machine Learning and Deep Learning tasks.

### 🗂️ Datasets Investigated:
1. **Tabular Data:** [Titanic Dataset](https://www.kaggle.com/c/titanic/data) (Survival prediction)
2. **Text Data:** [SMS Spam Collection](https://archive.ics.uci.edu/ml/datasets/sms+spam+collection) (Spam detection)
3. **Image Data:** [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html) (Object classification)

---

## 💡 Key Findings

### 1. Tabular Data (Titanic)
* **Missing Data:** Significant missing values in `Age` (~20%) and `Cabin` (>70%).
* **Survival Factors:** * Females had a drastically higher survival rate than males.
  * Passengers in 1st class (Pclass = 1) had the highest chance of survival.

### 2. Text Data (SMS Spam)
* **Class Imbalance:** The dataset is heavily imbalanced, with ~87% 'Ham' (normal) messages.
* **Length Distribution:** Spam messages are significantly longer on average and cluster at a higher character count compared to normal messages.
* **Vocabulary:** Spam messages frequently use promotional keywords (e.g., "FREE", "WIN", "Call").

### 3. Image Data (CIFAR-10)
* **Class Balance:** Perfectly balanced dataset (5,000 images for each of the 10 classes).
* **Pixel Statistics:** The Mean value of the Blue channel (~113.8) is lower than Red and Green, indicating an overall warmer tone in the dataset. 
* **Variance:** High standard deviation (~62-66) across channels reflects a high diversity in image contrast.

---

## 📂 Repository Structure

```text
├── 📓 Beng10 (1).ipynb          # Main Jupyter Notebook containing all EDA code
├── 📄 P4AI_BEN10.pdf            # Formal Assignment Report
├──  README.md                    # Project Landing Page
