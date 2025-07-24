# 🧠 AI-Based X-ray Diagnostic Report Generator

This project presents a multimodal AI system that automatically generates diagnostic reports from chest X-ray images using a combination of computer vision and natural language processing. The system uses a **Vision Transformer (ViT)** as the encoder and **GPT-2** as the decoder via Hugging Face’s `VisionEncoderDecoderModel` framework.

## 🚀 Project Highlights

- Built a vision-language model for automated chest X-ray report generation.
- Trained and evaluated on the **Indiana University Chest X-rays** dataset.
- Achieved a **BLEU score of 0.62** on test reports.
- Aims to improve radiological workflows and support healthcare in automating diagnostic narratives.

## 🛠️ Tools & Frameworks

- Hugging Face Transformers
- PyTorch
- VisionEncoderDecoderModel
- Indiana University Chest X-ray Dataset
- BLEU Score Evaluation

## 📊 Dataset

- Dataset used: **Indiana University Chest X-rays**
- Available at:  
  `/kaggle/input/chest-xrays-indiana-university`
- This dataset includes de-identified chest X-ray images with associated impression-level diagnostic reports.

## 📎 Notebook & Demo

For the complete code, training pipeline, model architecture, and sample outputs:

👉 **[View Full Project on Kaggle](https://www.kaggle.com/code/abhishekbuddiga/report-generator)**

## 📄 License

This project is for academic and research use only. Please cite the author when using this work in derived projects.

---

Feel free to fork this repo and explore how vision-language models can assist in medical reporting! 🩻📄
