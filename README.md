# 🩺 Dermatology Concept Detection using MONET

This project demonstrates **AI-based dermatological concept detection** using the **MONET vision-language model**.
The model performs **zero-shot image classification**, meaning it can detect skin-related concepts from an image **without task-specific training**.

The notebook loads a skin image and compares it against a list of dermatological concepts to predict the **most likely skin conditions with confidence scores**.

---

## 📌 Project Overview

Skin condition detection is an important application of **AI in healthcare and dermatology**.
This project uses a **vision-language transformer model** that can match images with text descriptions of skin conditions.

The model predicts possible dermatological features such as:

* erythematous
* scaly
* hyperpigmented
* hypopigmented
* papular
* nodular
* vesicular
* ulcerated
* crusted
* acne
* eczema
* psoriasis
* rosacea
* fungal infection
* skin cancer

The model outputs the **top predicted concepts with probability scores**.

---

## 🧠 Model Used

Model: **chanwkim/monet**

MONET is a **vision-language model designed for dermatology concept detection**.
It uses joint embeddings of images and text to determine which dermatological concepts best match the input image.

---

## ⚙️ Technologies Used

* Python
* PyTorch
* HuggingFace Transformers
* NumPy
* Pandas
* PIL (Python Imaging Library)

---

## 📂 Repository Structure

```
code.ipynb                     # Main notebook containing the full implementation
monetderma_output_images.pdf   # PDF containing input image and model output examples
```

---

## ▶️ How to Run the Project

1. Install dependencies

```
pip install torch transformers pillow numpy pandas
```

2. Open the notebook

```
code.ipynb
```

3. Run all cells to

* Load the MONET model
* Process the input image
* Detect dermatological concepts
* Display the top predictions

---

## 📊 Example Output

Example prediction from the model:

```
Top Concepts Detected:

erythematous : 62.3%
eczema : 21.1%
psoriasis : 9.3%
acne : 4.7%
rosacea : 2.6%

The most likely condition is: erythematous
```

The **input images and prediction outputs** are available in the file:

```
monetderma_output_images.pdf
```

---

## ⚠️ Disclaimer

This project is created for **educational and research purposes only**.
It is **not intended to be used as a medical diagnostic tool**.

---

## 👩‍💻 Author

Neha
AI / Machine Learning Enthusiast
