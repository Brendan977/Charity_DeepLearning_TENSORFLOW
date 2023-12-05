Alphabet Soup Charity - Deep Learning

Overview: 
The purpose of this analysis is to support the non-profit foundation Alphabet Soup and their mission of funding applicants with high chances of success. 


Results

DATA PREPROCESSING:
  -Target Variable: "IS_SUCCESSFUL"
  -Features Variable: "APPLICATION_TYPE", "AFFILIATION", "CLASSIFICATION",	"USE_CASE",	"ORGANIZATION",	"STATUS", "INCOME_AMT",	"SPECIAL_CONSIDERATIONS", "ASK_AMT"
  -"EIN" and "NAME" should be removed from the dataset because they are non-beneficial to the model.

COMPLING, TRAINING, AND EVALUATING THE MODEL:
  -For optimization purposes, I included an additional third layer with the nodes set as: First Layer: 8, Second Layer: 5, Third Layer: 3.
  -After multiple tries I was not able to achieve target performance for the model, the highest percent of accuracy reached was 73. 
  -In addtition to adding another hidden layer, I tried different node amounts, as well as ran the model to different size epochs: 50, 100, 125, 150. All attempts slightly increased accuracy above the original 72% but did not exceed 75%.

Summary: 
In summary, after multiple attempts, the model was able to reach 73% accuracy of correctly identifying worthy applicants within the training data. If having to replicate the process to potentially increase accuracy, I would consider further preprocessing of the data and making sure outliers or irrelevant features were not negatively effecting the data samples. I believe this could potentially increase higher chances of success for the model to better classify its targets.   


