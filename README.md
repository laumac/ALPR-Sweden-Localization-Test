ALPR Regional Localization Test (Sweden)

## 📌 Project Overview
This project is a specialized Quality Assurance (QA) analysis of an Automatic License Plate Recognition (ALPR) system, specifically focusing on the **Swedish market requirements**. 

The goal was to validate the system's performance on standard Swedish license plates (3 letters + 3 digits / 6 characters total) and identify regional detection gaps.

## 🧪 Test Scenarios
* **Plate Length Validation:** Identifying if the detected plate matches the 6-character Swedish standard.
* **Accuracy Breakdown:** Comparing the performance of the system on standard vs. non-standard plate formats.
* **Data Cleaning:** Removing whitespaces and handling 'None' detections to ensure data integrity.

## 📊 Key Metrics (Results)
* **Total Samples:** 100
* **Swedish Standard Plates (6 chars):** [Įrašyk savo skaičių, pvz. 85]
* **Accuracy on Standard Plates:** [Įrašyk savo %, pvz. 88%]
* **Non-Standard/Invalid Plates:** [Įrašyk savo skaičių, pvz. 15]

## 🛠 Tools Used
* **Python / Pandas:** For data manipulation and filtering.
* **Matplotlib:** For visualizing error distribution.
* **Google Colab:** As the primary testing environment.

## 💡 Conclusions & Recommendations
* The system shows **higher/lower** accuracy on 6-character plates compared to the general dataset.
* **Recommendation:** The OCR model needs fine-tuning for Swedish fonts to reduce character mismatches in standard formats.
