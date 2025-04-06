# NLP - Βασικές Ασκήσεις (Assignment 1)

Αυτό το repository περιλαμβάνει την πρώτη εργασία για το μάθημα **Φυσική Γλώσσα και Επεξεργασία Κειμένου (NLP)**. Η εργασία είναι χωρισμένη σε δύο βασικές ενότητες, καθεμία εκ των οποίων συνοδεύεται από αρχείο **notebook (.ipynb)** και **αρχείο PDF (.pdf)**.

## 📂 Περιεχόμενα

### Ενότητα A: Tokens, Types, Νόμος του Zipf
- `assignment_1_A.ipynb` – Το Jupyter Notebook με ανάλυση της πρώτης ενότητας.
- `assignment_1_A.pdf` – Έκδοση σε PDF του notebook για παρουσίαση ή εκτύπωση.

Σε αυτή την ενότητα:
- Γίνεται επεξεργασία του αρχείου `wsj_untokenized.txt`.
- Εφαρμόζεται tokenization.
- Υπολογίζονται tokens και types.
- Εξετάζεται η ισχύς του Νόμου του Zipf.

---

### Ενότητα B: N-gram Language Models
- `assignment_1_B.ipynb` – Το Jupyter Notebook με την εφαρμογή n-gram μοντέλων γλώσσας.
- `assignment_1_B.pdf` – Αντίστοιχο PDF του notebook.

Σε αυτή την ενότητα:
- Εκπαιδεύονται bigram και trigram μοντέλα.
- Υπολογίζεται η πιθανότητα και το perplexity.
- Εξετάζεται η προσέγγιση add-k smoothing.

---

## 🧪 Εξαρτήσεις
Η εργασία υλοποιείται σε περιβάλλον **Conda** το οποίο μπορεί να αναπαραχθεί εκτελώντας το ακόλουθο:

```
conda env create -f environment.yml
conda activate <το-όνομα-του-env>
```

Επιπλέον, χρησιμοποιείται το corpus `treebank` από το NLTK. Βεβαιωθείτε ότι έχετε κάνει download τα απαραίτητα δεδομένα με:

```python
import nltk
nltk.download('treebank')
