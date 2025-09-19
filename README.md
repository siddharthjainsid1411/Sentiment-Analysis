# Sequence-to-Sequence Transliteration with RNNs and Attention

This project implements **character-level sequence-to-sequence models** for the task of **transliterating Indian names into Hindi**.  
The focus is on exploring **encoder-decoder architectures** with and without **attention mechanisms**, and evaluating their performance on a parallel corpus of names.

## Features
- **RNN Encoder-Decoder Models**
  - Implemented with LSTM units
  - Character-level tokenization
- **Attention Mechanism**
  - Soft attention (Bahdanau-style)
  - Attention visualization with heatmaps
- **Training Framework**
  - Custom trainer for model-agnostic training
  - Checkpointing and resume support
- **Evaluation Metrics**
  - Accuracy
  - Edit Distance
  - Character Error Rate (CER)
  - Token Error Rate (TER)
  - BLEU Score
- **Decoding Strategies**
  - Greedy decoding
  - Attention-based decoding

## Dataset
- Parallel corpus of Indian names and their Hindi transliterations
- Preprocessing and tokenization using a custom character-level tokenizer

## Technologies
- Python (3.9+)  
- PyTorch  
- NumPy, Pandas  
- NLTK (for BLEU score)  
- Matplotlib (for attention visualization)  

## How to Run
```bash
# Install dependencies
pip install torch numpy pandas matplotlib nltk tqdm

# Run the main script
python nlp_assignment3.py
```

## Author
**Siddharth Jain**  
M.Tech in Robotics and Autonomous Systems, IISc Bengaluru
