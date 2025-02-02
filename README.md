# Vietnamese News Article Topic Classification

## Project Description
This project classifies Vietnamese news articles into one of 12 topics using the following approaches:  
1. **Basic Machine Learning (ML) algorithms**  
2. **RNN (Recurrent Neural Networks)**  
3. **LSTM (Long Short-Term Memory)**  
4. **PhoBERT** (a powerful pre-trained language model specifically for Vietnamese).  
## Dataset: 
Crawling from https://vnexpress.net/

---

## Installation Guide

### 1. General Requirements
- Python 3.8 or later  
- GPU (recommended for PhoBERT or deep learning models)

---

### 2. Running ML, RNN, and LSTM Models
1. Clone or download the project from GitHub:  
   ```bash
   git clone <github_link>
   cd <project_directory>
   ```
2. Open the **`ML+RNN+LSTM IntroAI project group 16.ipynb`** file in Jupyter Notebook or Google Colab.  
3. Click **Run All** to execute the code.  

---

### 3. Running the PhoBERT Model
1. Upload the file **`vietnamese_words.txt`** to your environment.  
2. Open the **PhoBERT notebook** file in Google Colab.  
3. Click **Run All** to execute the code.

---

## Project Structure
- **ML+RNN+LSTM IntroAI project group 16.ipynb**: Notebook containing implementations of Ml algorithm: Decision Tree, Random Forrest, XGBoost;DL model: RNN, and LSTM models.  
- **vietnamese_words.txt**: A vietnamese stopwords file for data preprocessing.
- **PhoBERT notebook**: Contains the implementation of the PhoBERT-based classifier.  

---

## Contact & Contribution
For questions or contributions, please feel free to reach out via GitHub or submit a pull request.  
