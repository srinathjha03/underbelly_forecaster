Project Report: Underbelly Peak Hour Forecaster
Student: Srinath Jha
Registration no: 25BCE10179

Course: Fundamentals of AIML

Problem: Predicts unpredictable wait times at the Underbelly eatery to help students optimize their schedules.

1. Methodology

Model: Decision Tree Regressor. Chosen for its ability to handle "spiky" non-linear data (like sudden lunch rushes) better than simple linear regression.

Data: A 60-day synthetic dataset simulating real campus patterns (1 PM peaks and 5 PM post-class spikes).

Features: Day of the week (encoded numerically) and Hour of the day.

2. Implementation

Preprocessing: Used LabelEncoder for categorical day data.

Evaluation: Used an 80/20 train-test split. The Mean Absolute Error (MAE) serves as the primary metric to determine prediction reliability.

3. Reflection

Logic over Complexity: Prioritized an interpretable model over a "black-box" neural network. A Decision Tree clearly maps out the "if-then" logic of student traffic.

Learning: The project demonstrates that feature engineering (like identifying specific rush hours) is more vital for accuracy than model depth.

4. Conclusion
This project applies supervised learning to a local, observable problem, proving that purposeful execution and clear data-driven logic are key to a successful AIML solution.
