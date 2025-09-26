


# Gemma-2B LoRA Fine-Tuning for Text-to-SQL

🚀 This repository demonstrates how to fine-tune **Gemma-2B** using **LoRA (Low-Rank Adaptation)** for the **Text-to-SQL** task.  
It includes training, evaluation, and inference workflows inside a Jupyter Notebook.

---

## 📌 Features
- Fine-tuning **Gemma-2B** with **LoRA** adapters
- Efficient parameter updates with minimal compute
- Dataset preparation for Text-to-SQL
- Training, validation, and evaluation pipeline
- Example inference: natural language → SQL queries

---

## 📂 Repository Structure
```

├── gemma2b-finetuned-lora-text2sql.ipynb   # Main notebook (training + inference)
├── README.md                               # Project documentation

````

---

## ⚡ Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/Srinivasulu2003/gemma2b-lora-text2sql.git
cd gemma2b-lora-text2sql
````

### 2. Install dependencies

```bash
pip install -r requirements.txt
```


### 3. Run the notebook

Open the Jupyter notebook and execute the cells:

```bash
jupyter notebook gemma2b-finetuned-lora-text2sql.ipynb
```

---

## 🧠 Example Usage

**Input (Natural Language):**

```
Show me the names of all customers who ordered more than 3 products.
```

**Output (Generated SQL):**

```sql
SELECT name FROM customers WHERE order_count > 3;
```

---

## 📊 Results

* Model: **Gemma-2B + LoRA**
* Task: **Text-to-SQL**
* Improvements: Lower training cost with LoRA, high-quality SQL generation


---

## 📜 License

This project is released under the MIT License.
Feel free to use and modify for research or production.

---

## 🙌 Acknowledgements

* [Google Gemma](https://ai.google.dev/gemma) for the base model
* [PEFT (LoRA)](https://huggingface.co/docs/peft/index) for parameter-efficient fine-tuning
* [Hugging Face Datasets](https://huggingface.co/docs/datasets/) for dataset handling


