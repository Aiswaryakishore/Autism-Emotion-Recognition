# Model Results

## Dataset Summary

### Initial Dataset
- Total: 881 images  

### After Augmentation
- Total: 3524 images  

### Final Balanced Dataset
- Total: 6872 images  

---

## Data Split

- Training: 4806 images  
- Validation: 1033 images  
- Test: 1033 images  

---

##  Model Performance

### MobileNet + SE
- Train Accuracy: 93.47%
- Validation Accuracy: 87.32%
- Test Accuracy: 85.58%
- Precision: 0.86
- Recall: 0.86
- F1 Score: 0.86
- Computation Time: 124.33 sec

---

### Vision Transformer (ViT)
- Train Accuracy: 98.69%
- Validation Accuracy: 90.39%
- Test Accuracy: 90.60%
- Precision: 0.91
- Recall: 0.91
- F1 Score: 0.91
- Computation Time: 2290.36 sec

---

###  Ensemble Model
- Test Accuracy: **98.55%**
- Precision: **0.99**
- Recall: **0.99**
- F1 Score: **0.99**
- Computation Time: 111.19 sec

---

##  Classification Report (Ensemble)

| Class   | Precision | Recall | F1-score | Support |
|--------|----------|--------|----------|---------|
| Angry  | 1.00     | 0.96   | 0.98     | 265     |
| Happy  | 1.00     | 0.99   | 0.99     | 254     |
| Neutral| 0.97     | 1.00   | 0.98     | 253     |
| Sad    | 0.98     | 0.99   | 0.99     | 260     |

---

##  Observations

- Ensemble model significantly improved performance over individual models  
- Vision Transformer outperformed MobileNet individually  
- Ensemble achieved near-perfect classification (98.55%)  
- Strong generalization with balanced dataset  
