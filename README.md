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
Crowd Sourced Emotional Multimodal Actors Dataset (CREMA-D)
https://github.com/CheyneyComputerScience/CREMA-D

### How to run
1. Clone Github repo: https://github.com/tiffanyhltse/cs663-final-ml-project
2. Download data: https://drive.google.com/drive/folders/1S4vR3UQ1-JvKyqqh9KHCBhhLsyQVcHuk?usp=sharing
3. Paste the whole data folder in the repo's root directory. Open Jupyter notebook and run the .ipynb files accordingly, can be any orders, totally up to you.

### File tree
- cs663-final-ml-project
    - data
        - mfcc_mel*
        - AudioWAV*
        - 2d_mfcc*
        - demo_mfcc*
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

### [https://docs.google.com/presentation/d/17xu0_qzgtfR6XQrorcgNNfy8uQbT2i1e/edit?usp=sharing&ouid=106516828913598115079&rtpof=true&sd=true](Presentation)
