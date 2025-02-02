(Python) Implementing AdaBoost for Predicting Online Shoppers' Purchase Intentions

AdaBoost, short for Adaptive Boosting, is a powerful ensemble learning algorithm that improves the accuracy of weak learners by combining them into a strong model. It works by iteratively training weak learners, such as decision stumps, and assigning higher weights to samples that are misclassified.

In the previous study, a system was proposed to predict online shoppers' intentions (whether they will buy or not) by analyzing various classification algorithms, including Random Forest, Decision Tree, Support Vector Machine, Gradient Boosting, AdaBoost, LightGBM, and CatBoost. The experiments were conducted using an online shoppers' intention dataset.

In our work, we further explore the impact of different numbers of estimators on the performance of the AdaBoost model. Specifically, we test 9 different values for n_estimators of 10, 50, 100, 150, 200, 250, 300, 350, 400, and observe similar results. Our work achieved accuracy of 90.56% compared to 89.14%, F1 score of 66.18% compared to 63.26%, precision of 74.27% compared to 69.34%, and recall of 59.69% compared to 58.17%. This investigation helps validate the robustness of the AdaBoost model and its performance across varying configurations.

authors with contact info

Diksha Krishnan, diksha_krishnan@brown.edu

Dongyan Sun, dongyan_sun@brown.edu

Shen Yu, shen_yu@brown.edu

Xinyu Zhou, xinyu_zhou1@brown.edu

Required library versions:

python=3.10.5

matplotlib=3.5.2

pandas=1.4.2

scikit-learn=1.1.1

numpy=1.22.4

xgboost=1.5.1

shap=0.40.0

jupyter_client=7.3.1

jupyter_core=4.10.0

jupyterlab=3.4.2

jupyter_server=1.17.0

jupytext=1.13.8

rise=5.7.1

plotly=5.8.0

ipywidgets=7.7.0
