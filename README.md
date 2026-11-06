# Student Loan Repayment Risk with Deep Learning

Predicts whether a student-loan applicant is likely to repay, using a neural network on credit-related features such as payment history, GPA ranking and STEM degree score.

**Approach:** scale the features → build a sequential neural network in Keras (two hidden layers, sigmoid output) → train with binary cross-entropy and Adam → evaluate on test data

**Result:** 62.5% test accuracy. The notebook also discusses what data a student-loan *recommendation system* would need, and which filtering method it would use.

**Notebook:** `M18_Starter_Code/student_loans_with_deep_learning.ipynb`

**Tools:** Python, pandas, scikit-learn, TensorFlow/Keras

*Coursework from the OSU AI Bootcamp.*
