# 🔮 AI Content Generation with GANs and GPT-2

This repository contains two generative AI notebooks:
1. **Image Generation using GANs** trained on the MNIST dataset.
2. **Text Generation using GPT-2** from Hugging Face's Transformers library.

Each notebook demonstrates how pre-trained deep learning models can be used to generate novel content—images and text—by learning from existing data.

---

## 🖼️ Project 1: Image Generation with GANs

This notebook implements a basic GAN using TensorFlow and Keras to generate handwritten digit images similar to the MNIST dataset.

### 📌 Highlights
- Dataset: **MNIST**
- Models: **Fully Connected Generator and Discriminator**
- Output: **28x28 grayscale images**
- Noise vector dimension: **100**

### 🚀 Run Instructions
1. Open `Generate_Images_with_GANs.ipynb` in any Jupyter Notebook environment (e.g., Google Colab, JupyterLab).
2. Execute all cells to train the GAN and visualize the outputs.

---

## 📝 Project 2: Text Generation with GPT-2

This notebook uses a pretrained GPT-2 model to generate coherent short stories from user-defined prompts.

### 📌 Highlights
- Model: **GPT-2 (Small)**
- Library: **Hugging Face Transformers**
- Prompts: Custom or predefined sentences
- Output: AI-generated short stories (up to 100 tokens)

### 🚀 Run Instructions
1. Open `Text_Generation_with_GPT.ipynb` in any Jupyter Notebook platform (preferably GPU-enabled for better performance).
2. Run all cells to load the model and generate text based on your chosen prompts.

---

## 🧰 Requirements

- Any Jupyter Notebook platform with a good processor (GPU recommended).
- All necessary dependencies are listed and installed within the respective notebooks.

---

## 💡 Author

This project was created for educational purposes to explore the capabilities of Generative Adversarial Networks and Transformer-based models in creative AI content generation.

---

