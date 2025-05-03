**Aquifer Properties Machine Learning Project**

Description

This project models the hydraulic conductivity and other aquifer properties using machine learning. The dataset is synthetically generated and includes features such as depth, sand fraction, clay fraction, and porosity. The dataset is used to predict the hydraulic conductivity of aquifers using a Random Forest Regressor.

Dataset

The synthetic dataset contains the following columns:

Depth: Depth of the aquifer (in meters).

SandFraction: Fraction of sand content in the soil.

ClayFraction: Fraction of clay content in the soil (calculated based on sand fraction).

Porosity: The porosity of the aquifer, affected by sand and clay fractions.

HydraulicConductivity: The target variable, representing the aquifer’s hydraulic conductivity.

Files
aquifer_properties_synthetic_data.xlsx: The generated dataset with synthetic values for the aquifer properties.

aquifer_modeling.py: Python script to generate synthetic data, train a machine learning model, and evaluate its performance (based on the dataset).

**Requirements**
To run the project, you'll need to install the following Python libraries:

numpy

pandas

scikit-learn

matplotlib

seaborn

You can install these libraries using pip:

bash
Copy
Edit
pip install numpy pandas scikit-learn matplotlib seaborn
How to Use
Download the dataset: You can download the synthetic dataset (aquifer_properties_synthetic_data.xlsx) from the project folder.

Run the script:

Download or clone the repository.

Run the aquifer_modeling.py script to train a machine learning model and predict hydraulic conductivity based on the features.

Analyze the results: The script will output performance metrics (Mean Squared Error and R² Score) and provide a scatter plot comparing actual vs predicted hydraulic conductivity.

Example
bash
Copy
Edit
python aquifer_modeling.py
This will output the Mean Squared Error and R² score and display a plot showing the model’s performance.

Author
Tarinabo williamtarinabo@gmail.com
