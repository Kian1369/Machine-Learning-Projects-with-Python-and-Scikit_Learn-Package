# Mushroom Classification with Boosting Methods

This project focuses on classifying mushrooms as either edible or poisonous using boosting methods such as AdaBoost and Gradient Boosting with GridSearch. The dataset used in this project contains various characteristics of mushrooms, including attributes like cap shape, surface, color, odor, gill attachment, and more. The primary goal is to create a robust predictive model and identify key features that can help in distinguishing between edible and poisonous mushrooms.

## Data

The dataset used for this project is sourced from the UCI Machine Learning Repository: [Mushroom Dataset](https://archive.ics.uci.edu/ml/datasets/Mushroom). It includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms from the Agaricus and Lepiota family. Each species is identified as definitely edible, definitely poisonous, or of unknown edibility (combined with poisonous for this analysis).

## Project Structure

1. **Data Analysis and Visualization**
   - Performed exploratory data analysis to understand the distribution and importance of various features.
   - Visualized the data using count plots and bar plots to identify key characteristics influencing mushroom edibility.

2. **Feature Engineering**
   - Converted categorical features to numerical using one-hot encoding.
   - Identified features with the highest predictive power.

3. **Model Building**
   - Implemented AdaBoost and Gradient Boosting classifiers.
   - Used GridSearch to optimize hyperparameters for the Gradient Boosting model.
   - Evaluated model performance using metrics like accuracy, precision, recall, and F1-score.

4. **Results**
   - AdaBoost with a single decision tree achieved a high accuracy, demonstrating the power of boosting methods even with simple base learners.
   - Identified 'odor' as a critical feature for classification, where mushrooms with any odor are highly likely to be poisonous.

## Key Findings

- Boosting methods, particularly AdaBoost, significantly improve classification performance by combining weak learners.
- The 'odor' attribute is a crucial indicator for distinguishing between edible and poisonous mushrooms.
- The project demonstrates the practical application of machine learning techniques in solving real-world classification problems.

## Conclusion

This project showcases the effectiveness of boosting methods in mushroom classification and highlights the importance of feature selection in building accurate predictive models. The findings provide valuable insights for mushroom foragers and contribute to the broader field of machine learning applications in biology and safety.

## License

This project is licensed under the MIT License.

