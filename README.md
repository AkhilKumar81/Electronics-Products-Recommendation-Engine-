### 🔌 Electronics Product Recommendation System (Content-Based)

### 📌 Problem

Online stores sell many electronic products like laptops, phones, and smartwatches. But customers often get confused because of too many options.  
They may miss similar or better products just because they are hard to find.

---

### 💼 Business Need

E-commerce platforms want to:
- Help users find similar products easily
- Improve user experience and satisfaction
- Increase product visibility and sales

---

### 🎯 Project Goal

Build a recommendation system that:
- Suggests similar electronic products
- Uses product features like "Wireless", "Touchscreen", etc.
- Works even if the user is new (no past history needed)

---

### 🛠️ How It Works

1. Load and clean the product data  
2. Combine product name + features  
3. Convert text to numbers using **TF-IDF**
4. Compare products using **cosine similarity**
5. Show top 5 most similar products

Bonus: Also used **fuzzy matching** to handle small spelling mistakes in product names.

---

### 🧪 Example Use

- If user selects a phone with "5G", "Fast Charging", etc.,  
  the system will show other phones with similar features.

---

### 🧰 Tools & Libraries

- Python  
- Pandas, NumPy  
- Scikit-learn  
- TF-IDF Vectorizer  
- Cosine Similarity  
- FuzzyWuzzy (for optional fuzzy matching)

---

### 📁 Dataset

- A sample dataset created for learning.
- Columns: `product_id`, `product_name`, `product_features`

---

### ✅ Final Conclusion

- I built a smart recommendation system using text-based product features.  
- It shows similar gadgets even without needing user history.  
- I also added fuzzy matching to handle spelling mistakes.  
- This type of system can be useful in online stores to improve product discovery.  
- It was a great learning project using text processing, similarity scoring, and simple logic.

---

### ▶️ How to Run

1. Open the notebook in Jupyter or Google Colab  
2. Run all cells  
3. Type a product name or index to see similar product suggestions

---
