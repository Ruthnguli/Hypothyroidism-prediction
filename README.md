# Hypothyroidism-prediction

Hypothyroidism is a condition where thyroid glands do not produce enough thyroid hormones in the bloodstream lowering metabolism. The first hypothroidism was first described by Thomas Curling in 1850 and the cause and suitable treatment were established after 1883.
Major symptoms include fatigue, cold sensitivity, constipation, dry skin and unexplained weight gain. Hypothyroidism is treated by replacing thyroid hormones.

# objective

To study and build a model that determines whether or not the patient's symptoms indicate that the patient has hypothyroid.

# Approach 1: Decision Tree

- use at least 2 out of the 3 advanced models we have studied: Random forests, Ada boosted trees, and gradient boosted trees.
- Try and optimize each of the 2 models, making sure to document how you've set up your hyperparameters.
- Identify which of the 2 models you trust most, and use your model to determine which features are most impactful in influencing the prediction.
-
# Approach 2: SVM

- Apply Polynomial, linear and rbf kernel function to build your SVM model and then evaluate their performance and pick the kernel that performs the best. Remember to tune your parameters to improve the performance of your model. To make your life easier, make sure to visualize the models you've created. Use any two features to build the models for this step.

# Dataset

Nairobi Hospital conducted a clinical camp to test for hypothyroidism. The data collected focused on Thyroid patients

# Dataset Columns

Age
Sex
on_thyroxine
query_on_thyroxine
on_antithyroid_medicationthyroid_surgery
query_hypothyroid
query_hyperthyroid
pregnant
sick
tumor
lithium
goitre
TSH_measured
TSH
T3_measured
T3
TT4_measured
TT4
