**Data_Preprocessing**

- Import libraries
- Import Dataset
- Handle Missing Data
    - SimpleImputer
- Handle Categorical Data
    - ColumnTransformer, OneHotEncoder
    - LabelEncoder
- Split Dataset to TrainSet and TestSet

- Feature Scaling
    - Standardization/Normalization
    
--------------------------------------------------------------------------------------------------------------
- We should do Train Test Split before Feature Scaling, to avoid information Leakage.
- Test Set should be a brand new dataset.
- In Feature Scaling, StandardScalar works all time. NormalScalar when some features follow Normal distribution.
- Apply Feature Scaling to numerical data, no need to apply on Dummy Variables.



