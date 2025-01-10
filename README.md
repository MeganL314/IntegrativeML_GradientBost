# IntegrativeML_GradientBost
Integrative machine learning pipeline for small or wide datasets to determine biomarkers associated with treatment specific outcomes

### Train the model on all patients
#### 1. Remove correlated features

#### 2. Balance dataset with SMOTE to generate synthetic samples for the minority class  
<br/><br/>
  

### Leave one out cross-validation
#### Remove measurements that were only assigned to incorrect predictions (measured by model accuracy)  

  <br/><br/>

### Calculate SHAP and permutation importance of each feature
#### Identify measurements prioritized by feature importance   


 <br/><br/> 
### Resulting measurements used in Cox PH and logistic regression
#### Tested transformations of selected biomarkers  

