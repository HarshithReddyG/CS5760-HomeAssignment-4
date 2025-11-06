# Home Assignment 4 – README

## Author Information

* Name: Harshith Reddy Gundra
* Course: CS5760 – Natural Language Processing
* ID: 700780724
* Email: [hxg07240@ucmo.edu](mailto:hxg07240@ucmo.edu)
* Assignment: Home Assignment 4

---

## Folder Structure

The assignment is organized into two main parts:

1. Short-answer theoretical PDFs (Q1–Q6)
2. Programming notebooks/scripts (P2-Q1 to P2-Q3)

```
CS5760-HomeAssignment-4/
│── Q1/q1.pdf                 # Theoretical solution for Question 1
│── Q2/q2.pdf                 # Theoretical solution for Question 2
│── Q3/q3.pdf                 # Theoretical solution for Question 3
│── Q4/q4.pdf                 # Theoretical solution for Question 4
│── Q5/q5.pdf                 # Theoretical solution for Question 5
│── Q6/q6.pdf                 # Theoretical solution for Question 6
│── P2-Q1/p2-q1.ipynb         # Character-level RNN language model notebook
│── P2-Q1/p2-q1.py            # Optional Python script version
│── P2-Q2/p2-q2.ipynb         # Mini Transformer Encoder notebook
│── P2-Q2/p2-q2.py            # Optional Python script version
│── P2-Q3/p2-q3.ipynb         # Scaled Dot-Product Attention notebook
│── P2-Q3/p2-q3.py            # Optional Python script version
│── README.md                 # This file
```

---

## Details

### Part I – Short Answers (Q1–Q6)

* Each PDF contains theoretical explanations, formulas, and diagrams for the respective question.
* Covered topics include:

  * RNN families and I/O patterns
  * Vanishing gradients and remedies
  * LSTM gates and cell state
  * Self-attention and scaled dot-product attention
  * Multi-head attention and Add & Norm
  * Encoder-decoder with masked attention

### Part II – Programming (P2-Q1 to P2-Q3)

* **P2-Q1 – Character-Level RNN:**

  * Embedding → LSTM → Linear → Softmax model
  * Supports temperature-controlled text generation
  * Includes training loss curves and sample generated sequences

* **P2-Q2 – Mini Transformer Encoder:**

  * Tokenization, embedding, sinusoidal positional encoding
  * Multi-head self-attention, feed-forward layer, Add & Norm
  * Outputs contextual embeddings and attention heatmaps

* **P2-Q3 – Scaled Dot-Product Attention:**

  * Implements formula: `Attention(Q,K,V) = softmax(QK^T / sqrt(d_k)) V`
  * Demonstrates raw scores, scaled scores, attention weights, and output vectors
  * Includes softmax stability check and heatmap visualization

---

## How to Run

1. Open `.ipynb` notebooks in Google Colab.
2. Execute all cells sequentially.
3. Optional: Run `.py` scripts locally if preferred.
4. PDFs can be viewed independently for theoretical explanations.

---

## Notes

* All code is commented and modular.
* Each notebook is standalone, so you can execute Q1–Q3 independently.
* Visualizations (attention heatmaps, embeddings, loss plots, generated text) are included for clarity.
* Submission includes both PDFs (theory) and notebooks/scripts (programming).

---

GitHub Repository: [https://github.com/HarshithReddyG/CS5760-HomeAssignment-4](https://github.com/HarshithReddyG/CS5760-HomeAssignment-4)
