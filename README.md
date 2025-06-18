# Jamboree Education – Admission Success Prediction

This project analyzes the admission data of Jamboree Education applicants to predict the likelihood of being admitted into a U.S. university based on key academic factors. The project uses **Linear Regression** to model relationships and generate interpretable insights to support student strategy and university counseling.

---

## Objective

To identify the most influential academic parameters that affect the chances of admission, and to build a regression model to **predict admission probability** based on features like **GRE score, TOEFL score, CGPA, Letter of Recommendation strength , SOP , Research, University Rating**.

---

## Key Insights

- **GRE Score and CGPA** are the most influential predictors of admission.
- **SOP and LOR ratings** show moderate impact but less than GPA.
- TOEFL score is less correlated compared to CGPA and GRE.
- The final model achieved strong performance with interpretable coefficients.

---

## Techniques & Tools Used

- Python, Google Colab
- Pandas, NumPy
- Seaborn, Matplotlib
- Statsmodels (for OLS regression)
- Exploratory Data Analysis (EDA)
- Outlier treatment using IQR
- Multicollinearity detection using VIF

---

## Model Summary

- Built Linear Regression model using `statsmodels.OLS`
- Removed features with high multicollinearity
- Used adjusted R² to evaluate model quality
- Interpreted feature weights to derive actionable advice

---

## Business Impact

This model can help:
- Students understand how much weight universities place on CGPA vs other metrics
- Counselors guide students on where to improve to increase their admission chances
- Build “what-if” tools for students to simulate different score scenarios

---

## Author

**Prakhar Asthana**
[Linkedin] : www.linkedin.com/in/prakhar-asthana-5b3a8b131


