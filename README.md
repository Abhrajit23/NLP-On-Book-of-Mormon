# 📖 Book of Mormon Text Analysis

### Author: Abhrajit Das

---

## 🧾 Overview

This project applies **Natural Language Processing (NLP)** techniques using Python’s **NLTK** library to analyze the **Book of Mormon**. The goal is to uncover patterns in word usage, common contexts, and linguistic structure, offering deeper insights into the themes and language of the text.

---

## 📚 Dataset

* **File:** `book_of_mormon.txt`
* **Source:** Full text of the Book of Mormon (translated by Joseph Smith, Jr.)
* **Encoding:** ISO-8859-1
* **Size:** Full text corpus

---

## 🧹 Text Preprocessing

* Tokenization using `nltk.word_tokenize`
* Creation of searchable text using `nltk.Text`
* Cleaning and formatting for consistent analysis

---

## 🔍 Analysis Components

### 1️⃣ Word Frequency Analysis

* **Goal:** Identify the most frequently used words
* **Tool:** `nltk.FreqDist`
* **Output:** List of top words with counts

### 2️⃣ Concordance Analysis

* **Goal:** Find occurrences and surrounding context of specific words (e.g., *Christ*)
* **Tool:** `text.concordance("Christ")`
* **Insight:** Understand how key religious terms are used throughout the text

### 3️⃣ Similarity Analysis

* **Goal:** Find words used in similar contexts as *Christ*
* **Tool:** `text.similar("Christ")`
* **Insight:** Discover related terms and thematic associations

### 4️⃣ Common Contexts

* **Goal:** Explore shared contexts for word pairs like *Jesus* and *Christ*
* **Tool:** `text.common_contexts(["Jesus", "Christ"])`
* **Insight:** Analyze word-pair relationships and theological themes

### 5️⃣ Dispersion Plot

* **Goal:** Visualize keyword distribution over the corpus
* **Tool:** `text.dispersion_plot(["Christ", "repentance", "love", "sin", "faith"])`
* **Insight:** Track the location and density of core religious themes

---

## ✅ Conclusion

This analysis showcases the use of **NLP in religious text mining**, revealing patterns in usage, themes, and structure within the Book of Mormon. These techniques can be extended to other scriptures or large textual corpora for comparative religious studies, linguistics, or digital humanities research.

---

## 📬 Contact

For questions, feedback, or collaboration:
📧 **[abhrajit.breathin@gmail.com](mailto:abhrajit.breathin@gmail.com)**
🔗 [LinkedIn](https://www.linkedin.com) | 🌐 [Open-talk.co](https://open-talk.co)
