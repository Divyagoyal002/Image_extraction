# **Amazon ML Challenge**

## **Problem Overview**

We have a dataset with the following components:

1. **Image Link**: URL to the product's image.
2. **Category**: The product category.
3. **Entity Name**: The attribute whose value needs to be predicted (e.g., weight, height).
4. **Actual Value**: The true value of the entity (e.g., "50 grams", "15 cm"). This value is absent in the test data.

### **Objective**
Train a machine learning model to predict the entity value (e.g., "12 grams" or "15 cm") from the image URLs in the test data.

### **Evaluation Metric**
Predictions will be evaluated using the F1 score, which balances precision and recall.

### **Constraints**
- Use only specific units provided in the appendix.
- Ensure the prediction file format adheres to the validation checker requirements.

---

## **Our Approach**

### ***1. Text Extraction from Images Using OCR***

- **OCR Technology**: We utilize Optical Character Recognition (OCR) technology to extract text data from the images.
- **Tool**: The EasyOCR method is employed to perform this extraction, converting visual text within images into machine-readable text.

### ***2. Data Preprocessing and Entity Extraction***

- **Data Preprocessing**: The code involves cleaning and standardizing text data (e.g., replacing commas with periods, handling ambiguous characters).
- **Entity Extraction**: Logic is implemented for extracting specific entities and their associated values from text based on predefined mappings and patterns.

---

## **Getting Started**

### **Prerequisites**
- Python 3.x
- Required libraries (list the libraries you used, e.g., EasyOCR, pandas, etc.)

### **Installation**
1. Clone the repository:
   ```bash
   git clone <repository-url>
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
### Contributing
If you would like to contribute to this project, please fork the repository and submit a pull request.
