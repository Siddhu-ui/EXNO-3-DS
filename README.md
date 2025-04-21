## DEVELOPED BY : SIDDHARTH S
## REGISTER NO: 212224040317

## EXNO-3-DS

# AIM:
## To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:

![DS exp 3 ipynb - Colab_page-0001](https://github.com/user-attachments/assets/ffab6170-51a1-43c9-bd4f-2b616291dddc)


![DS exp 3 ipynb - Colab_page-0002](https://github.com/user-attachments/assets/b24f4743-cbef-4f49-9805-25876220fd79)


![DS exp 3 ipynb - Colab_page-0003](https://github.com/user-attachments/assets/414bb2f0-bf8e-4059-8068-739df119f41c)


![DS exp 3 ipynb - Colab_page-0004](https://github.com/user-attachments/assets/57acbf80-36e5-49cd-b736-5e1e0a278ea5)


![DS exp 3 ipynb - Colab_page-0005](https://github.com/user-attachments/assets/2b47b1e9-fb0f-4623-a985-71ea5851e6bf)


![DS exp 3 ipynb - Colab_page-0006](https://github.com/user-attachments/assets/e71dee05-140b-4d8b-a31e-b0a3fe65d0e5)


![DS exp 3 ipynb - Colab_page-0008](https://github.com/user-attachments/assets/8786e792-ffaa-4921-bb59-44f6a0e275fa)


![DS exp 3 ipynb - Colab_page-0009](https://github.com/user-attachments/assets/690b6dd2-7859-4f1a-b032-33c10f1e3f5e)


# RESULT:

Data successfully read, encoded, transformed, and saved as processed_data.csv.

       
