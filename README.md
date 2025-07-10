## **Overview**
This project is a small personal initiative to kickstart my journey in learning Python and machine learning. The goal is to predict the number of Olympic medals a country might win in a given year based on historical data.

The model is trained on data from previous Olympic years, using the number of medals won and athletes entered by each country. It then generates predictions for a later year using the same input features. The model’s performance is evaluated by comparing its predictions to actual results, with error measured as the absolute difference between predicted and actual medal counts.

#### **Packages used:**
- pandas
- numpy
- scikit-learn
- seaborn
- ipykernel

### **Conclusion:**
While using past medal counts and the number of athletes per country provided reasonably accurate predictions for nations with large delegations, the model performed poorly for countries with fewer participants. To improve future predictions, incorporating individual athlete performance data (if any) could offer a more granular and reliable basis for estimating medal outcomes.
