# CS663 final project
Final project update for CS 663 Machine Learning

## Human emotion detector
For our final project, we decided to create a speech classifier that can detect human emotion by their voice. In this project, we aim to discern six different emotions from ~7K+ audio speeches.

### Members
- Tiffany Tse
- Shulin Li
- Jake Zhong

### Professor
David Guy Brizan

### Data source
https://github.com/CheyneyComputerScience/CREMA-D

### How to run
Download data: https://drive.google.com/drive/folders/1S4vR3UQ1-JvKyqqh9KHCBhhLsyQVcHuk?usp=sharing
Clone Github repo: https://github.com/tiffanyhltse/cs663-final-ml-project

Paste the whole data folder in the repo's root directory. Open Jupyter notebook and run the .ipynb files accordingly.

### File tree
cs663-final-ml-project
    - data
        - mfcc_mel
        - AudioWAV
        - 2d_mfcc
        - original_mfcc_data.csv
        - VideoDemographics.csv
    - 1_EDA.ipynb
    - 2_feature_exploration.ipynb
    - 3_baseline_SVM_KNN_LSTM.ipynb
    - 4_baseline_CNN.ipynb
    - 5_mfcc_mel_LSTM.ipynb
    - 6_mfcc_CNN_final.ipynb
    
### Insights of models
- Baseline models:
    - 3_baseline_SVM_KNN_LSTM.ipynb
    - 4_baseline_CNN.ipynb
- Final models:
    - 5_mfcc_mel_LSTM.ipynb
    - 6_mfcc_CNN_final.ipynb