# VocalAI- Depression Detection 

**Author**: Atiyyah Limalia

![image](https://github.com/user-attachments/assets/91c7f9da-0fa3-4256-857a-f14e089fc4b5)


## Repository Structure

- <b>README.md:</b> The top level README for reviewers of this project
- <b>first_notebook.ipynb:</b> Beginning narrative documentation of analysis in jupyter notebook up through the data cleaning stages
- <b>first_notebook.ipynb:</b> Beginning narrative documentation of analysis in jupyter notebook up through the data cleaning stages
- <b>first_notebook.ipynb:</b> Beginning narrative documentation of analysis in jupyter notebook up through the data cleaning stages
- <b>first_notebook.ipynb:</b> Beginning narrative documentation of analysis in jupyter notebook up through the data cleaning stages
- <b>first_notebook.ipynb:</b> Beginning narrative documentation of analysis in jupyter notebook up through the data cleaning stages
  

## Abstract

- This study explores **speech-based methods** to predict **depression severity** using the **DAIC-WOZ dataset**.  
- It compares the performance of **machine learning** and **deep learning models**.  
- Models are trained on **OpenSMILE-extracted features**, including **prosodic**, **formant**, and **spectral characteristics**, as well as **deep features** from **spectrograms**.  
- **Preprocessing techniques** like **noise reduction** and **segmentation** are applied to ensure **data quality** and **consistency**.  
- **Machine learning models**, especially **XGBoost**, perform best with an **RMSE of 2.93**.  
- **Deep learning models**, such as **EfficientNet** and **ResNet**, yield **RMSEs of 6.92** and **6.93**, but struggle to predict **extreme scores**.  
- A **custom CNN architecture** provides **broader prediction coverage** but has a higher **RMSE of 7.77**, showing difficulty in modeling **complex spectrogram features**.  
- **Prediction distribution analysis** reveals both the **strengths** and **limitations** of each model, particularly for **extreme PHQ-8 scores**.


## Background and Context

- **Clinical depression** is a widespread disorder marked by sadness, fatigue, and loss of interest, which affects daily life.  
- If **left untreated**, it can lead to serious outcomes like **self-harm** and **suicide**.  
- **Early detection** is essential but challenging due to varying symptoms and the absence of a clear clinical definition.  
- **Traditional diagnosis methods** rely on subjective self-reports and clinician observations, which can be **inconsistent** and **biased**.  
- A lack of trained professionals and resources highlights the need for **automated, scalable solutions**.  
- **Voice** has emerged as a promising tool—it's **non-invasive**, **cost-effective**, and supports **remote monitoring**.  
- Handcrafted **vocal features** like **pitch**, **energy**, and **formants** have shown success in machine learning but can miss subtle cues and introduce **human bias**.  
- **Deep learning models** learn directly from raw audio, capturing complex structures and reducing reliance on manual feature selection.  
- Prior studies are limited and often lack **comprehensive evaluation** and **explainability** of model predictions.  
- This study aims to **compare machine learning and deep learning approaches**, focusing on both **accuracy** and **explainability** for depression detection.






