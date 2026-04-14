# swat-flood-xgboost-2025
Swat KPK Flood Prediction 2025
Using TensorFlow Deep Learning
Study Area
Swat Valley, KPK, Pakistan

## Data Used
Sentinel-1 SAR Before Flood (GEE)
Sentinel-1 SAR During Flood (GEE)
SRTM DEM 30m (GEE)
Slope derived from DEM (GEE)
CHIRPS Rainfall data (GEE)

## Methods
Data balancing using SMOTE
xgboost
Binary classification

## Results
Test Accuracy: 99.58%
No Flood F1: 0.99
Flood F1: 1.00

## TensorFlow vs XGBoost Comparison

| Metric            | TensorFlow | XGBoost | Winner        |
|------------------|------------|---------|--------------|
| Accuracy         | 99.88%     | 99.58%  | TensorFlow   |
| Flood Recall     | 1.00       | 1.00    | Both ✅       |
| No Flood Recall  | 1.00       | 0.99    | TensorFlow   |
| Training Speed   | Slower     | Faster  | XGBoost ✅    |
| Feature Importance | No       | Yes     | XGBoost ✅    |

##Explanation
TensorFlow shows slightly higher overall accuracy, which means it performs better in correctly identifying both flooded and non-flooded areas. It also achieves perfect recall for both flood and no-flood classes, making it highly reliable for detection tasks. However, TensorFlow models are slower to train and do not easily provide feature importance, which makes them harder to interpret.
On the other hand, XGBoost performs almost as well in terms of accuracy but is significantly faster to train and provides clear feature importance, helping us understand which inputs influence the predictions. While its no-flood recall is slightly lower, the difference is minimal.
Overall, TensorFlow is better for maximum accuracy, while XGBoost is more efficient and interpretable, making it useful for practical and real-time applications.
