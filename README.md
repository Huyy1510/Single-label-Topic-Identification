# Single-label-Topic-Identification
# Vietnamese Topic Classification with PhoBERT  
This project fine-tunes **PhoBERT** for **topic classification** on the Vietnamese **NEU-ESC dataset**.   
The dataset contains 10 topic categories (e.g., Academic, News, Service, ...).   
We apply **weighted loss** to handle class imbalance and evaluate on the official test split.


## 📊 Evaluation Results

| Metric       | Score  |
|--------------|--------|
| Accuracy     | 0.75   |
| Macro-F1     | 0.60   |
| Precision    | 0.57   |
| Recall       | 0.66   |

### Example Predictions
![Demo Predictions](https://github.com/Huyy1510/Single-label-Topic-Identification/blob/main/assests/Example.png)
