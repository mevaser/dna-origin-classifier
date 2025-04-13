# 👬 DNA Origin Classification using Markov Chains & HMM

This notebook analyzes DNA sequences and classifies them as most likely originating from one of three organisms:

- 🧝 Human  
- 🦠 Corona virus  
- 🧫 Cholera bacterium  

The project is based on an advanced data science assignment involving probabilistic modeling and sequence analysis.

---

## 🔍 Methods Used

### 🔢 Part A – Log-Likelihood Classification
- Build **Markov transition matrices** from DNA sequences
- Compute **log-likelihood (LL)** of an unknown sequence against each organism
- Classify the sequence origin based on LL scores

### 🤖 Part B – Hidden Markov Model (HMM)
- Use **emission probabilities** per nucleotide (A, C, G, T) for each organism
- Use **transition probabilities** between organisms (hidden states)
- Apply the **Viterbi algorithm** to determine the most likely organism for each nucleotide
- Output a full predicted organism path for the sequence

---

## 💫 Sample Output

```
🧬 Test Sequence: AAACCTACGCCCGT
📊 Most likely organism per nucleotide:
A → Human
A → Human
...
G → Human
T → Human

✅ Conclusion: Sequence most likely originates from Human
```

---

## 📁 Files

- `DNA-Origin-Classification-Markov-HMM.ipynb` – The full Jupyter notebook with code, explanations, and results.


---

## 🛠️ Technologies

- Python (Colab / Jupyter)
- pandas, numpy
- Hidden Markov Model
- Viterbi Algorithm
- Data visualization (optional)

---

## ✍️ Author

**Mevaser Zehoray**  
Computer Science, Ruppin Academic Center  
[LinkedIn](https://www.linkedin.com/in/mevaser-zehoray)

