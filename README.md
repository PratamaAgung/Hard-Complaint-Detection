# Hard-Complaint-Detection
This repository will be used as the report for hard complaint detection research in an Indonesia's e-commerce  

## Experiment Result
|          Algoritma         | Prerpocessing | Feature Extractor         | Average F1-score (10-Fold) |
|:--------------------------:|:-------------:|---------------------------|----------------------------|
| Rule Based                 | -             | -                         | 0.76565                    |
| Rule Based                 | Normalization | -                         | 0.76561                    |
| SVM + Rule Based           | -             | TF                        | 0.95914                    |
| SVM + Rule Based           | Normalization | TF                        | 0.95628                    |
| SVM + Rule Based           | Normalization | TF with min_occurence     | 0.95135                    |
| SVM + Rule Based           | -             | TF-IDF                    | 0.96206                    |
| SVM + Rule Based           | Normalization | TF-IDF                    | 0.96496                    |
| SVM + Rule Based           | Normalization | TF-IDF with min_occurence | 0.96404                    |
| Random Forest + Rule Based | -             | TF                        | 0.94744                    |
| Random Forest + Rule Based | Normalization | TF                        | 0.94649                    |
| Random Forest + Rule Based | Normalization | TF with min_occurence     | 0.94840                    |
| Random Forest + Rule Based | -             | TF-IDF                    | 0.94745                    |
| Random Forest + Rule Based | Normalization | TF-IDF                    | 0.94747                    |
| Random Forest + Rule Based | Normalization | TF-IDF with min_occurence | 0.95134                    |