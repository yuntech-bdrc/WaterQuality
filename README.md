# WaterQuality

This study is based on XGBoost to classify water resources and predict their safety, and uses SHAP to explain the model.
  
    
![image](https://github.com/yuntech-bdrc/WaterQuality/blob/main/image/Screenshot%202024-09-22%20133107.png)

## Requirement  
 
``` shell
pip install -r requirement.txt
```

## Performance
| Accuracy | Precision | Recall | F1-score |
| :-- | --: | --: |:--:|
| water-potability | 0.77 | 0.73 | 0.66 | 0.7 |
| water-quality | 0.96 | 0.93 | 0.78 | 0.85 |

## Datasets
[water-potability](https://www.kaggle.com/datasets/adityakadiwal/water-potability "kaggle_water_potability")  
[water-quality](https://www.kaggle.com/datasets/mssmartypants/water-quality "kaggle_water_quality")

## References

[SHAP](https://arxiv.org/abs/1705.07874 "A Unified Approach to Interpreting Model Predictions")  
[TreeSHAP](https://arxiv.org/abs/1802.03888 "Consistent Individualized Feature Attribution for Tree Ensembles")  
[XGBoost](https://arxiv.org/abs/1603.02754 "XGBoost: A Scalable Tree Boosting System")  
