**Project Title: Comprehensive Cleaning and Modeling of Used Car Data**

**Description:**
This project revolves around the thorough cleaning and subsequent modeling of a dataset comprising information regarding used cars. The dataset, obtained from Quikr Car listings, presented numerous inconsistencies and errors that needed meticulous handling before conducting any modeling tasks. The primary objective was to preprocess the dataset effectively, addressing missing values, correcting data types, removing irrelevant entries, and standardizing data formats, followed by building a predictive model to estimate car prices based on various features.

**Steps Taken:**
1. **Data Import and Exploration**:
   - Imported the dataset into a Pandas DataFrame for initial exploration.
   - Conducted exploratory data analysis (EDA) to identify anomalies and inconsistencies.
   - Examined the distribution and relationships between different features.

2. **Data Cleaning**:
   - **Inconsistent Data Handling**:
     - Removed entries with non-year information in the 'year' column.
   - **Missing Values Imputation**:
     - Dropped rows with missing values in crucial columns like 'kms_driven' and 'fuel_type'.
   - **Price Cleanup**:
     - Removed entries with 'Ask For Price' and stripped commas from price values.
   - **Kms Driven Standardization**:
     - Standardized 'kms_driven' values to contain only numeric data.
   - **Company Cleanup**:
     - Removed non-company names from the 'company' column.
   - **Name Standardization**:
     - Standardized car names to include only the first three words for consistency.

3. **Data Modeling**:
   - **Feature Engineering**:
     - Split the data into features (X) and target (y).
     - Applied one-hot encoding to categorical features using sklearn's OneHotEncoder.
   - **Model Selection and Training**:
     - Utilized a Linear Regression model for price prediction.
   - **Model Evaluation**:
     - Assessed model performance using metrics such as R-squared score.
   - **Fine-Tuning**:
     - Experimented with different models and hyperparameters to optimize performance.

**Files Included:**
- `quikr_car.csv`: Original dataset obtained from Quikr Car listings.
- `Cleaned_car_data.csv`: Dataset after thorough preprocessing.
- `car_modeling.ipynb`: Jupyter notebook containing the entire cleaning and modeling pipeline.
- `README.md`: Detailed Markdown file providing an overview, instructions, and acknowledgments.
- `requirements.txt`: Text file listing all necessary Python libraries and their versions for reproducibility.

**Instructions to Run:**
1. Clone the repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Open and execute the `car_modeling.ipynb` notebook in Jupyter or any compatible environment.


**Feedback and Contributions:**
Feedback and contributions are highly appreciated. Feel free to open an issue or pull request for any suggestions or improvements.

**Contact Information:**
For queries or further information, please reach out via email at aditi.work1111@gmail.com.
