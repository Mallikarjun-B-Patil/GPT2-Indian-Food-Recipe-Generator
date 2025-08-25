# GPT2 Indian Food Recipe Generator  

A Generative AI project that fine-tunes **GPT-2** to generate authentic Indian food recipes. The model was trained on a curated dataset of Indian dishes, including titles, ingredients, and cooking steps, and can generate complete recipes based on a given prompt.

---

## 📌 Overview  
This project leverages **GPT-2** for text generation to produce Indian food recipes. The model was fine-tuned on a dataset containing thousands of Indian dishes to generate realistic and culturally relevant recipes.  

The notebook includes:
- Data preprocessing
- GPT-2 fine-tuning using Hugging Face Transformers
- Recipe generation examples and evaluation

---

## ✅ Features  
- Fine-tuned GPT-2 on Indian recipe dataset  
- Generates **dish name, ingredients, and instructions**  
- Supports **custom prompts** to generate a recipe for a specific dish  
- Provides multiple recipe variations  


---

## 🛠️ Technologies Used  
- Python  
- Hugging Face Transformers  
- PyTorch  
- GPT-2  
- Google Colab (for training)  

---

## 📊 Dataset  
The dataset includes:  
- **Dish Name**  
- **Ingredients List**  
- **Cooking Instructions**  

Data preprocessing steps included text cleaning, removing special characters, and formatting recipes into a suitable structure for GPT-2 training.

---

## ⚙️ Model Training Details  
- **Base Model:** GPT-2  
- **Epochs:** 3  
- **Batch Size:** 2  
- **Learning Rate:** 5e-5  
- **Optimizer:** AdamW  
- **Loss after training:** ~1.89 (from notebook results)  

Training was done using Hugging Face `Trainer` API.

---

## ✅ Results & Insights  
After fine-tuning, the model was able to generate coherent and culturally relevant Indian recipes. Here are some examples:  

### **Example 1**  
**Prompt:** *Paneer Butter Masala*  

