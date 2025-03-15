# 🛒 E-commerce Classification

## 📌 Project Overview
This 🏗️ focuses on classifying e-commerce 🏷️ into four 📂:
- 🏠 Household
- 📱 Electronics
- 👕 Clothing & Accessories
- 📚 Books

Using **📊 TF-IDF Vectorization** for 📈 feature extraction and **🌳 Random Forest Classifier** for 🎯, the 🤖 categorizes 🏷️ based on their 📝.

## 📂 Dataset
The 📂 consists of 🏷️ descriptions labeled with one of the four 📂. It is 🛠️ to remove 🔊 and irrelevant 📃 features.

## 🛠️ Tech Stack
- **🖥️ Language:** 🐍 Python
- **📦 Libraries:** 📚 Scikit-learn, 🏗️ Pandas, 🔢 NumPy, 📊 Matplotlib, 🎨 Seaborn

## 🔄 Project Workflow
1. **🧹 Data Preprocessing:**
   - 🧽 and 🔧 📝
   - Removing ❌ stopwords and ✂️ punctuation
2. **🛠️ Feature Engineering:**
   - Using 📊 TF-IDF for 📈 transformation
3. **📚 Model Training:**
   - 🏋️‍♂️ a 🌳 Random Forest on the transformed 📃
4. **📏 Model Evaluation:**
   - 📏 accuracy, precision, recall, and 🏆 F1-score
   - 📊 confusion matrix
5. **🔮 Prediction:**
   - 🔍 product 📂 for new 🔤

## ⚙️ Installation
### 📌 Prerequisites
Ensure you have 🐍 installed, then install 🔧:
```bash
pip install scikit-learn pandas numpy matplotlib seaborn
```

## 🚀 Usage
Run the `main.py` 📜 to 🏋️‍♂️ and 🧪 the 🤖:
```bash
python main.py
```
For making 🔮 on new 🏷️ descriptions, modify and execute:
```python
model.predict(tfidf_vectorizer.transform(["New product description"]))
```

## 📊 Results
- Achieved **🔥 accuracy** on 🧪 📃.
- 🌳 Random Forest 🎯 traditional 🤖 in text classification.

## 🔜 Future Enhancements
- 🧪 with 🤖 deep learning (LSTMs, BERT)
- 📈 feature selection techniques
- 🌍 as a 🕸️ API for ⏳ classification

## 👤 Author
Developed by [Your Name] as part of an 🛒 classification 📜.

## 📝 License
This 🏗️ is licensed under the 📜 MIT License.

