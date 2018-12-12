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

This is the result with 1k dataset

|          Algoritma         | Prerpocessing | Feature Extractor         | Average F1-score (10-Fold) |
|:--------------------------:|:-------------:|---------------------------|----------------------------|
| Rule Based                 | -             | -                         | 0.7656                    |
| Rule Based                 | Normalization + stemmer | -                         | 0.8637                    |
| SVM + Rule Based           | -             | TF                        | 0.95914                    |
| SVM + Rule Based           | Normalization + stemmer | TF                        | 0.9621                    |
| SVM + Rule Based           | Normalization + stemmer | TF with min_occurence     | 0.9581                    |
| SVM + Rule Based           | -             | TF-IDF                    | 0.96206                    |
| SVM + Rule Based           | Normalization + stemmer | TF-IDF                    | 0.9766                    |
| SVM + Rule Based           | Normalization + stemmer | TF-IDF with min_occurence | 0.9699                    |
| Random Forest + Rule Based | -             | TF                        | 0.94744                    |
| Random Forest + Rule Based | Normalization + stemmer | TF                        | 0.9591                    |
| Random Forest + Rule Based | Normalization + stemmer | TF with min_occurence     | 0.9630                    |
| Random Forest + Rule Based | -             | TF-IDF                    | 0.9435                   |
| Random Forest + Rule Based | Normalization + stemmer | TF-IDF                    | 0.9562                    |
| Random Forest + Rule Based | Normalization + stemmer | TF-IDF with min_occurence | 0.9640                    |

This is the experiment with 2k dataset

|          Algoritma         | Prerpocessing | Feature Extractor         | Average F1-score (10-Fold) |
|:--------------------------:|:-------------:|---------------------------|----------------------------|
| Rule Based                 | -             | -                         | 0.7399                    |
| Rule Based                 | Normalization + stemmer | -                         | 0.8291                    |
| SVM + Rule Based           | -             | TF                        | 0.9542                    |
| SVM + Rule Based           | Normalization + stemmer | TF                        | 0.9566                    |
| SVM + Rule Based           | Normalization + stemmer | TF with min_occurence     | 0.9482                    |
| SVM + Rule Based           | -             | TF-IDF                    | 0.9686                    |
| SVM + Rule Based           | Normalization + stemmer | TF-IDF                    | 0.9721                    |
| SVM + Rule Based           | Normalization + stemmer | TF-IDF with min_occurence | 0.9701                    |
| Random Forest + Rule Based | -             | TF                        | 0.9417                    |
| Random Forest + Rule Based | Normalization + stemmer | TF                        | 0.9532                    |
| Random Forest + Rule Based | Normalization + stemmer | TF with min_occurence     | 0.9547                    |
| Random Forest + Rule Based | -             | TF-IDF                    | 0.9447                   |
| Random Forest + Rule Based | Normalization + stemmer | TF-IDF                    | 0.9547                    |
| Random Forest + Rule Based | Normalization + stemmer | TF-IDF with min_occurence | 0.9547                    |