# Student-performance
This project tries to predict Student's final maths test grade based on their features/qualities.

## Data: [UCI Machine learning repository](https://archive.ics.uci.edu/ml/datasets/Student+Performance)

# Objectives
Two main objectives of this project is to:
  1. Predict student's grades with high accuracy.
  2. Find out which features does the most influence to student's performance.

# Training
For this project I'm using Linear Regression, Decision Tree and Random forest models to predict **G3 math test** grades. 
# Results
## Correlation results
Apart from other test results most of the things didn't really matter, but it shouldn't be very suprising because most of our performance capabilities are predetermined by genes. If you want to know more about correlations I highly recommend reading book called [Freakonomics](https://www.amazon.com/Freakonomics-Economist-Explores-Hidden-Everything/dp/0060731338), where you can find a chapter on this exact subject.
## Machine learning results

| Model | Mean Squared Error(MAE) |
| --- | --- |
| Linear Regression | 4.13 |
| Random Forest | 4.79 |
| Decision Tree | 6.06 |

As you can see Linear Regression did the best job, but other models weren't that far.
### Dataset Citation
P. Cortez and A. Silva. Using Data Mining to Predict Secondary School 
Student Performance. In A. Brito and J. Teixeira Eds., Proceedings of 
5th FUture BUsiness TEChnology Conference (FUBUTEC 2008) pp. 5-12, 
Porto, Portugal, April, 2008, EUROSIS, ISBN 978-9077381-39-7. [Web link](http://www3.dsi.uminho.pt/pcortez/student.pdf)

