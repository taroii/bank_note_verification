# Bank Note Verification  
### By Taro Iyadomi
##### April 2 - 6, 2023  

This project is part of AI Camp's Summer 2023 Data Science Internship training program. The goal of this project is to build a data science application from start to finish, using technologies like Matplotlib/Seaborn, XGBoost, and Flask.  

I will be predicting the validity of bank notes based on several features. These features were obtained through a Wavelet Transform tool which extracted features such as variance, skewness, curtosis, and entropy of bank notes. This data is from [UCI's machine learning repository](https://archive.ics.uci.edu/ml/datasets/banknote+authentication) and can be downloaded directly from [kaggle](https://www.kaggle.com/datasets/ritesaluja/bank-note-authentication-uci-data).  

This will be used to differentiate between (or classify) real and forged bank notes. This project can be extended to incorporate image classification (computer vision) so that users can upload their own bank notes to determine (within a certain confidence) if those bank notes are legitimate. On top of that, we can provide a questionnaire to understand the origins of the bank note of question (such as whether it was from a real bank or if it was given as change from a random vendor). We may not have the data for the latter, but it would be an interesting problem to solve.  

