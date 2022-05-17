# Credit_Risk_Analysis

## Results

### RandomOverSampler model
<p align="center">
  <img src="https://github.com/joZecodes/Credit_Risk_Analysis/blob/main/RandomOverSampler.png">
</p>

<br><br>

### SMOTE model
<p align="center">
  <img src="https://github.com/joZecodes/Credit_Risk_Analysis/blob/main/SMOTE.png">

</p>
<br><br>

### ClusterCentroids model
<p align="center">
  <img src="https://github.com/joZecodes/Credit_Risk_Analysis/blob/main/ClusterCentroids.png">

</p>
<br><br>

### SMOTEENN model
<p align="center">
  <img src="https://github.com/joZecodes/Credit_Risk_Analysis/blob/main/SMOTEENN.png">

</p>
<br><br>


### BalancedRandomForestClassifier model
<p align="center">
  <img src="https://github.com/joZecodes/Credit_Risk_Analysis/blob/main/BalancedRandomForestClassifier.png">

</p>
<br><br>


### EasyEnsembleClassifier model
<p align="center">
  <img src="https://github.com/joZecodes/Credit_Risk_Analysis/blob/main/EasyEnsembleClassifier.png">

</p>
<br><br>

## Summary
In general, the models used to perform the credit risk analysis are not very precise in determining whether a credit risk is high or not.
However, EasyEnsembleClassifier, which has a 92% recall rate, can detect almost all credit that banks and lenders consider high risk. Because of a low precision, the bank may still miss business opportunities by misdetecting low-risk credits as high risk, penalizing its credit strategy and negatively impacting its revenue.
For those reasons I would not recommend the bank to use any of these models to predict credit risk.
