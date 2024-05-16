# Car Insurance Claim
This repository investigates the influence of bias in car insurance claims using experimental methods. Utilizing a dataset of car insurance policyholders' information, including demographic attributes such as age, gender, and race, we develop a classification model to predict the likelihood of policyholders filing insurance claims.

## Introduction
In an era where artificial intelligence (AI) is increasingly prevalent in the insurance sector, concerns about bias and discrimination embedded in machine learning (ML) algorithms have arisen. This experiment employs a Random Forest ML algorithm to explore potential biases associated with demographic factors, particularly gender, in car insurance claims. The objective is to identify and address bias within the dataset, providing insights for policymakers and insurers to promote fairness and accountability in AI usage.

## Dataset
The Car Insurance Data sourced from Kaggle forms the basis of this study, comprising 10,000 observations with 19 variables, including demographic and insurance-related attributes.

## Installation
To run the code in this repository, you'll need to install the necessary libraries
```
pip install numpy pandas seaborn matplotlib scikit-learn scipy
```
1. Clone or download the repository to your local machine.
2. Open the Jupyter Notebook or Python script containing the model implementation.
3. Run the code to train the model, evaluate its performance, and analyze the results.


## Performance Metrics
Various metrics including accuracy, precision, recall, and F1-score were utilized to evaluate the model's performance. Additionally, fairness criteria such as equal accuracy, demographic parity, and equal opportunity were employed to assess bias.

## Findings and Discussion
While the overall model performance was satisfactory, gender-based analysis revealed significant biases favoring certain groups, particularly males. Evaluation against fairness criteria highlighted disparities in prediction accuracy and opportunities between genders, underscoring the need for ethical considerations in model development and usage.

![Performance metrics for checking for Fairness criteria](https://github.com/Rapheehat/Car_Insurance_Claim/assets/167440482/c581e8ba-f9a4-457b-b688-c28e46f118de)

## Conclusion
This project underscores the importance of fairness and transparency in machine learning models, particularly in sensitive domains like insurance. While our study focused on gender bias, future research should explore mitigation strategies for biases related to other protected characteristics. Ultimately, ensuring fairness in AI models is essential for upholding societal values and preventing perpetuation of inequalities.

## Contributing
Contributions to this project are welcome. If you would like to contribute, please follow the standard GitHub workflow and submitting a pull request.

## License
This project is licensed under the MIT License. You are free to modify, distribute, and use the code and resources in this repository according to the terms of the license.

## Contact
For any questions or inquiries related to this project, please contact the project owner.
Email: ajiboderafiat@yahoo.com
