# 🩺 Predicting Diabetes Risk Using Lifestyle & Socioeconomic Indicators  
### A Predictive Analytics Case Study (BRFSS 2015)

**Tools Used:** R | Logistic Regression | Random Forest | LDA | ROC Analysis  
**License:** MIT  

---

## 📌 Business Problem

Diabetes is a growing public health challenge in the United States. Early identification of high-risk individuals can significantly improve prevention strategies and reduce long-term healthcare costs.

This project develops predictive models to classify diabetes status using lifestyle, health, and socioeconomic indicators from the Behavioral Risk Factor Surveillance System (BRFSS) 2015 dataset.

The objective is to:
- Identify significant risk factors
- Compare predictive modeling techniques
- Evaluate model performance for potential screening applications

---

## 📊 Dataset

**Source:** CDC Behavioral Risk Factor Surveillance System (BRFSS) 2015  

The dataset includes health-related survey responses from U.S. adults across multiple states.

### Key Variable Categories:
- Lifestyle factors (physical activity, smoking, diet)
- Health indicators (BMI, blood pressure)
- Socioeconomic indicators (income, education)
- Demographics

**Target Variable:**  
Binary classification of diabetes status

---

## 🔍 Methodology

1. Data cleaning and preprocessing  
2. Feature selection and variable encoding  
3. Train-test split  
4. Model development:
   - Logistic Regression  
   - Random Forest  
   - Linear Discriminant Analysis (LDA)  
5. Model evaluation using:
   - Accuracy  
   - Precision  
   - Recall  
   - F1 Score  
   - ROC-AUC  

---

## 📈 Model Comparison

The three models were evaluated based on predictive performance and interpretability.

- **Logistic Regression** provided interpretable odds ratios for understanding risk factors.
- **Random Forest** improved predictive accuracy by capturing nonlinear relationships.
- **LDA** offered a baseline comparison model.

(You can optionally insert your performance metrics here.)

---

## 🔎 Key Insights

- Higher BMI and physical inactivity were strongly associated with increased diabetes risk.
- Socioeconomic factors such as income and education showed measurable impact.
- Random Forest demonstrated stronger classification performance, while Logistic Regression offered clearer interpretability.

---

## 💡 Business & Public Health Implications

- Predictive modeling can support early risk screening initiatives.
- Healthcare organizations can target high-risk populations for preventive intervention programs.
- Understanding lifestyle and socioeconomic drivers enables more data-informed public health strategies.

---

## 📂 Repository Structure

```
docs/          # Reports and HTML outputs
outputs/       # Model outputs and result tables
README.md      # Project overview
LICENSE        # MIT license
```

---

## 📎 Deliverables

- Reproducible analysis in R  
- Model comparison results  
- Logistic regression coefficient table with odds ratios  
- Final written report (HTML / DOCX)

---

## 📬 Contact

For questions or collaboration opportunities, feel free to connect via LinkedIn or GitHub.
