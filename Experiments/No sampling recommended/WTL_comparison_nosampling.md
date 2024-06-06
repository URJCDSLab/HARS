| Sampling method         | Classifier    | Balance       | $O_p$           |
|-------------------------|---------------|---------------|---------------|
| ROS                     | DT            | __6-5-11__        | __7-5-10__        |
|                         | kNN           | __14-3-5*__       | __14-3-5*__       |
|                         | LR            | 7-3-12        | 6-3-13        |
|                         | MLP           | __11-1-10__       | 9-0-13        |
|                         | RF            | __10-3-9__        | 7-3-12        |
|                         | Linear SVM    | __11-5-6*__       | __10-5-7*__       |
|                         | RBF SVM       | 7-3-12        | 3-3-16*       |
|                         | XGB           | 6-4-12        | 6-4-12        |
| SMOTE                   | DT            | __8-4-10__        | 5-5-12        |
|                         | kNN           | __14-3-5*__       | __10-5-7*__       |
|                         | LR            | 7-3-12        | 6-3-13        |
|                         | MLP           | __11-1-10__       | 10-0-12       |
|                         | RF            | __8-3-11__        | 4-3-15*       |
|                         | Linear SVM    | __10-5-7*__       | __10-5-7*__       |
|                         | RBF SVM       | 5-2-15        | 4-3-15        |
|                         | XGB           | __8-4-10__        | __9-4-9__         |
| ADASYN                  | DT            | __8-4-10__        | 5-5-12        |
|                         | kNN           | __14-3-5*__       | __12-3-7*__       |
|                         | LR            | __11-2-9__        | 8-2-12        |
|                         | MLP           | __15-0-7*__       | __13-0-9__        |
|                         | RF            | __10-3-9__        | 5-3-14*       |
|                         | Linear SVM    | __13-5-4*__       | __10-5-7*__       |
|                         | RBF SVM       | __11-2-9__        | 7-2-13        |
|                         | XGB           | __10-4-8*__       | __7-4-11__        |
| RUS                     | DT            | __19-3-0*__       |               |
|                         | kNN           | __15-2-5*__       |               |
|                         | LR            | __13-2-7*__       |               |
|                         | MLP           | __20-0-2*__       |               |
|                         | RF            | __18-2-2*__       |               |
|                         | Linear SVM    | __15-3-4*__       |               |
|                         | RBF SVM       | __19-0-3*__       |               |
|                         | XGB           | __20-2-0*__       |               |
| Cluster centroids       | DT            | __18-4-0*__       |               |
|                         | kNN           | __14-4-4*__       |               |
|                         | LR            | __13-2-7*__       |               |
|                         | MLP           | __16-0-6*__       |               |
|                         | RF            | __17-2-3*__       |               |
|                         | Linear SVM    | __13-4-5*__       |               |
|                         | RBF SVM       | __15-2-5*__       |               |
|                         | XGB           | __15-4-3*__       |               |
| SMOTE + ENN             | DT            | __10-4-8*__       |               |
|                         | kNN           | __15-3-4*__       |               |
|                         | LR            | __12-2-8*__       |               |
|                         | MLP           | __15-0-7*__       |               |
|                         | RF            | __12-3-7*__       |               |
|                         | Linear SVM    | __13-5-4*__       |               |
|                         | RBF SVM       | __10-3-9*__       |               |
|                         | XGB           | __13-4-5*__       |               |
| SMOTE + Tomek           | DT            | __8-4-10__        |               |
|                         | kNN           | __14-3-5*__       |               |
|                         | LR            | __8-3-11__        |               |
|                         | MLP           | __13-1-8*__       |               |
|                         | RF            | 7-3-12        |               |
|                         | Linear SVM    | __11-5-6*__       |               |
|                         | RBF SVM       | 5-2-15*       |               |
|                         | XGB           | __8-4-10__        |               |



Win-tie-loss comparing the performance obtained with HARS, when it recommends not sampling,  against the state-of-the-art methods for each sampling method and each classifier. $O_p$ is only defined for oversampling. In bold are the cases where HARS performs better than alternatives. * means there is a significant difference between the compared methods with $\alpha = 0.1$.