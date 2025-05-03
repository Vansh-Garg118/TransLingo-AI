#  TransLingo-AI :-Attention-Driven English-French Translation

This project demonstrates an English-to-French Neural Machine Translation (NMT) system implemented in a single Jupyter Notebook using TensorFlow and Keras. The model uses a sequence-to-sequence (seq2seq) architecture with LSTM layers and a Luong-style attention mechanism to generate more fluent and context-aware translations.

---

## 📘 Notebook Contents

The notebook includes:

- Data cleaning and preprocessing of an English–French parallel corpus  
- Tokenization and vocabulary creation  
- Encoder–Decoder architecture with bidirectional LSTM and attention  
- Greedy and beam search decoding  
- Training and validation with EarlyStopping and learning rate scheduling  
- Attention heatmap visualization for word alignment analysis  

---

## 🛠️ Tech Stack

- Python 3.x  
- Google Colab 
- TensorFlow 2.x (with Keras)  
- NumPy, Pandas  
- Matplotlib, Seaborn  

---

## 📂 File Structure

- TransLingo_AI.ipynb # Main notebook with all code and documentation

---

## ▶️ How to Use

1. Clone or download this repository  
2. Open the notebook file `TransLingo_AI.ipynb` in Jupyter  
3. Run all cells to preprocess data, train the model, and view results  

---

## 📌 Notes

- Dataset used: English–French parallel corpus (e.g., from Tatoeba or similar)  
- All code and training logic are contained within the notebook  
- No external model files or APIs required  

---

## ✅ Future Enhancements

- Integrate subword tokenization (e.g., Byte Pair Encoding)  
- Add BLEU score evaluation  
- Convert to script-based implementation for API deployment  
- Try Transformer-based architecture for comparison

---
