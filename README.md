# **Text-to-Speech from Scratch** 🎙️🔊  

## **Overview**  
This project implements a **Text-to-Speech (TTS) system using Transformer architecture**. The model converts textual input into speech, leveraging deep learning techniques for high-quality voice synthesis.

## **Features** 🚀  
✔ **Uses Transformer-based architecture** for speech synthesis.  
✔ **Processes text into phonemes** with custom preprocessing.  
✔ **Generates mel spectrograms** from input text.  
✔ **Supports dynamic sequence masking** for handling variable-length inputs.  
✔ **Configurable Hyperparameters** for training and inference.

## **Installation** ⚙️  
Clone the repository and install dependencies:  
```bash
git clone https://github.com/tonmoy197/text-to-speech.git
cd text-to-speech
pip install -r requirements.txt
```

## **Usage** 🛠️  
Run the Jupyter Notebook for model training and inference:  
```bash
jupyter notebook text-to-speech-from-scratch.ipynb
```

## **Key Components** 📌  
### **1. Hyperparameter Configuration**  
- Defines model settings, input/output parameters, and training configurations.  
- Includes paths for dataset loading and preprocessing.  

### **2. Mask from Sequence Lengths Function**  
- Creates a mask tensor for handling variable-length sequences.  
- Ensures proper attention mechanism behavior.  

### **3. Text Preprocessing & Phoneme Mapping**  
- Converts text input into a numerical representation.  
- Maps phonemes to tokenized embeddings.  

### **4. Model Training and Inference**  
- Uses a Transformer-based architecture to learn text-to-speech mapping.  
- Generates mel spectrograms from textual input.  

## **Dataset Requirements** 📊  
The model requires a dataset containing **text-audio pairs** for training. Example datasets:  
- **LJSpeech**: High-quality single-speaker speech dataset.  
- **LibriTTS**: Large multi-speaker dataset.  

## **Contributing** 🤝  
We welcome contributions! If you want to improve this project, feel free to:  
✅ Submit an issue  
✅ Fork the repository and create a pull request  
✅ Add new language support or features  

## **License** 📜  
This project is licensed under the **MIT License**. Feel free to use and modify it!  
