# Depression Detection in Slack Messages Using Neuro-Symbolic AI
This project is designed to detect signs of depression in employee messages on Slack, leveraging a Neuro-Symbolic AI approach that combines machine learning with rule-based symbolic reasoning. The goal is to build a robust, interpretable model that can analyze messages and provide explainable insights into depression indicators.

## Project Overview
In this project, plan to develop a hybrid AI system that combines:

Neural components: Machine learning (ML) methods that learn patterns in text data.
Symbolic components: Rules based on keywords associated with depression symptoms.

### Objective
To detect and classify text messages indicating potential depression, improving both detection accuracy and interpretability through Neuro-Symbolic AI techniques.

### Development Steps
#### Step 1: Data Loading and Preprocessing
Data Cleaning: Removed URLs, special characters, and stopwords to ensure that the focus remains on meaningful words.
Outcome: Simplified, standardized text data that can be efficiently processed by ML algorithms and rule-based checks.

#### Step 2: Defining Symbolic Depression Indicators
Incorporated a symbolic approach by defining depression-related keywords:
Created a list of keywords commonly associated with depressive symptoms (e.g., "hopeless," "tired," "alone").
Added a depression_flag to indicate messages containing these keywords.
Outcome: This symbolic flag serves as a simple, rule-based feature that highlights messages potentially related to depression, enhancing interpretability.

#### Step 3: Combining Symbolic and ML Features
Vectorization: Used CountVectorizer to convert text data into numerical form (word frequency counts).
Hybrid Feature Set: Combined the vectorized text data with the symbolic depression flag to create a feature set that includes both types of information.
Outcome: A feature matrix containing both rule-based indicators and statistical word patterns, making the data suitable for Neuro-Symbolic AI modeling.

#### Step 4: Training the Hybrid Model
(Next Step) to be update..............

- Pubudu Piyumal