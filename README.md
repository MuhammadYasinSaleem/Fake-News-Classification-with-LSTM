# **Text Classification Using Bi-Directional LSTM**

This project implements a **text classification model** using a **Bi-Directional LSTM** (Long Short-Term Memory) network. The model processes textual data, classifies it into binary categories, and achieves high accuracy while preventing overfitting.

## **📌 Features**
- **Tokenizer**: Preprocesses text and converts words into sequences.
- **Embedding Layer**: Represents words as dense vectors.
- **Bi-Directional LSTM**: Captures sequential dependencies in text.
- **Dropout & Dense Layers**: Helps in reducing overfitting.
- **Binary Classification**: Uses sigmoid activation for output.

### 📊 Model Hyperparameters
| Parameter        | Value   |
|-----------------|---------|
| **Embedding Dim** | 128     |
| **LSTM Units**   | 128      |
| **Dense Layer 1** | 128 neurons (ReLU) |
| **Output Layer** | 1 neuron (Sigmoid) |
| **Batch Size**   | 64      |
| **Epochs**       | 2       |
| **Optimizer**    | Adam    |
| **Loss Function** | Binary Cross-Entropy |


## 📈 Results & Performance

| Training Run | Accuracy | Loss  | Validation Accuracy | Validation Loss |
|-------------|----------|-------|---------------------|----------------|
| **Run 1**   | 99.97%   | 0.0012 | 99.89%              | 0.0044         |
| **Run 2**   | 99.95%   | 0.0021 | 99.86%              | 0.0076         |
| **Run 3**   | **99.96%** | **0.0023** | **99.94%** | **0.0039** |

📌 **Best Model:** **Run 3** – Highest validation accuracy with lowest validation loss. 🚀


