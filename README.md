# Predictive Maintenance for Automobile Industries: A Data Mining Approach

This project explores the application of data mining and predictive analytics to enhance predictive maintenance (PdAM) in automobile industries, aligning with the Industry 4.0 approach. It includes a Python-based implementation for predicting car engine failure using sensor data.

## Overview

The research paper "Automobile Industries using Data Mining and Predictive Analytics: An Industry 4.0 Approach" [cite: 105, 106, 107, 108, 109] proposes a PdAM framework to help the automobile industry identify patterns using sensor data and predict equipment conditions, specifically wear and tear, before failure occurs[cite: 108]. This project puts those concepts into practice by developing a model to predict car engine failure.

![Screenshot 2025-05-13 210958](https://github.com/user-attachments/assets/ff708992-7a2c-4eff-98d1-89460c324a87)


## Key Concepts from the Research Paper

-   **Industry 4.0 and PdAM:** The project leverages the principles of Industry 4.0, which emphasizes smarter decision-making through advanced technologies for data collection and interpretation[cite: 105, 106]. PdAM is a key component, using sensor data to predict maintenance needs[cite: 108, 109].
-   **PdAM Framework:** The paper outlines a five-phase PdAM framework:
    1.  Data collection from various resources (sensors, IoT, data warehouses, etc.)[cite: 110].
    2.  Data pre-processing (cleaning, transformation, reduction)[cite: 111].
    3.  Algorithm selection (classification, regression, association)[cite: 112, 3].
    4.  Predictive maintenance model development[cite: 112].
    5.  Model training and testing for accurate results[cite: 112].
-   **Data Mining Algorithms:** The framework utilizes various algorithms, including classification, regression, and association, to support decision-making in the automobile industry[cite: 107, 117].
-   **Benefits of Predictive Analytics:** The research emphasizes that PdAM helps in early awareness of machine health, preventing damage, reducing downtime, improving safety, understanding failure causes, and increasing productivity and revenue[cite: 113, 114, 115, 116, 117, 118, 119, 125, 23, 24].

## Python Implementation: Predicting Car Engine Failure

The Python implementation (`PdAM.ipynb`) demonstrates a simplified version of the PdAM framework, focusing on predicting engine failure from sensor data.

![Screenshot 2025-05-13 211050](https://github.com/user-attachments/assets/ce50331a-8fe2-4f4f-aff2-476a5e46a416)


### Libraries Used

-   Pandas
-   NumPy
-   Seaborn
-   Scikit-learn (sklearn.model\_selection, sklearn.linear\_model)

### Data Pre-processing

-   Data types are analyzed.
-   Missing values are checked and handled.

### Exploratory Data Analysis (EDA)

-   EDA is performed to understand relationships between sensor measurements and engine failure.

  ![Screenshot 2025-05-13 210733](https://github.com/user-attachments/assets/1a1ae95b-5aa5-4825-a208-d017306b22b2)


### Modeling

-   The dataset is split into training and testing sets.
-   A Linear Regression model is used to predict engine failure. But the Rsquare ans RMSE score was not good so used Classification Algorythm model as it was a binary dataset and that's why linear regression does not performed well. (Note: The research paper mentions various algorithms) [cite: 112, 3]

  ![Screenshot 2025-05-13 210632](https://github.com/user-attachments/assets/5cb98e6b-61ea-4d7e-8247-6b339246118b)


### Files

-   `Car engine sensor data.csv`: Dataset containing car engine sensor data.
-   `PdAM.ipynb`: Jupyter Notebook with the Python implementation.

### Usage

1.  Install the required libraries.
2.  Place the data file in the same directory as the notebook.
3.  Run the notebook to execute the analysis and modeling.

## Alignment with Research Paper

This project aligns with the research paper by:

-   Applying the PdAM concept to a real-world problem (engine failure prediction)[cite: 108, 109].
-   Using sensor data as a key input for predictive maintenance[cite: 110, 116].
-   Implementing data pre-processing and modeling steps[cite: 111, 112].
-   Demonstrating the use of machine learning (Linear Regression) for predictive analytics, although the paper suggests a broader range of algorithms[cite: 112, 3, 119].
-   Focusing on the goal of predicting potential failures, which contributes to the benefits outlined in the paper, such as reducing downtime and improving safety[cite: 115, 23].

![Screenshot 2025-05-13 210905](https://github.com/user-attachments/assets/317ff5c6-6478-438c-9874-9adc2d11bb4e)


## Further Development

This project can be extended by:

-   Implementing other algorithms (classification, etc.) as suggested in the research paper[cite: 112, 3].
-   Incorporating more phases of the PdAM framework, such as data collection strategies and more advanced model evaluation[cite: 110, 112].
-   Expanding the dataset with more variables to align with the inputs mentioned in the paper (temperature, sound, vibration, pressure, RPM, etc.)[cite: 24].
