### 🧠 **Smart Product Pricing – Amazon ML Challenge 2025**

**Description:**
Developed an end-to-end Machine Learning solution for **predicting product prices** in e-commerce using data provided by Amazon. The dataset included product descriptions, attributes, and images, requiring multimodal feature extraction and model blending for optimal performance.

**Approach:**

* **Text Features:** Extracted product details using TF-IDF and BERT embeddings to capture semantic meaning.
* **Image Features:** Processed product images using pretrained CNNs (EfficientNet / CLIP) for visual embeddings.
* **Tabular Features:** Engineered numerical and categorical features like quantity, unit, and brand presence.
* **Modeling:** Trained ensemble models (LightGBM, CatBoost, and XGBoost) with stacking and out-of-fold validation.
* **Evaluation:** Optimized for **Symmetric Mean Absolute Percentage Error (SMAPE)**.
* **Result:** Achieved **49.45% OOF SMAPE**, ranking in the **top tier among 3700+ participating teams**.

**Tools & Tech:** Python, Pandas, Scikit-learn, LightGBM, CatBoost, OpenCV, TensorFlow / PyTorch, TF-IDF, BERT, CLIP

