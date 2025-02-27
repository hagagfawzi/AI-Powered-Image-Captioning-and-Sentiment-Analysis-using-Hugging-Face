# AI-Powered Image Captioning and Sentiment Analysis using Hugging Face  

## 📌 Overview  
This project integrates **Computer Vision (CV)** and **Natural Language Processing (NLP)** to develop an AI-powered system for **image captioning, sentiment analysis, and image-text retrieval**. Using **Hugging Face Transformers**, the model enhances image understanding and text interpretation through deep learning.  

## 🚀 Features  

### 🔹 1. Image Captioning  
- Utilizes **BLIP (Bootstrapped Language-Image Pretraining)**: `Salesforce/blip-image-captioning-base`.  
- Generates descriptive captions from images using **pre-trained pipelines** and **direct model loading**.  
- Useful for **accessibility, content tagging, and automated metadata generation**.  

### 🔹 2. Sentiment Analysis  
- Employs **RoBERTa-based sentiment analysis model**: `cardiffnlp/twitter-roberta-base-sentiment-latest`.  
- Analyzes text and classifies it as **positive, neutral, or negative**.  
- Can be applied to **social media monitoring, customer feedback analysis, and brand sentiment tracking**.  

### 🔹 3. Image-Text Matching (ITM)  
- Uses `Salesforce/blip-itm-base-coco` to determine **how well a caption matches an image**.  
- Computes **softmax-based probability scores** for text-image relevance.  
- Helps in **content verification, fake news detection, and media search engines**.  

## 🛠️ Technologies Used  
- **Deep Learning Frameworks**: `PyTorch`, `Transformers`  
- **Models**: `BLIP`, `RoBERTa`, `Vision Transformers`  
- **Computer Vision**: `PIL`, `torchvision`  
- **NLP**: `Tokenizers`, `PyTorch`  

## 📌 Applications  
✅ **Automated Image Captioning** – Enhancing accessibility for visually impaired users.  
✅ **Social Media Sentiment Analysis** – Understanding audience opinions and brand reputation.  
✅ **Content Verification & Fake News Detection** – Validating image-text authenticity.  
✅ **Multimodal AI Research** – Exploring text and vision model intersections for AI advancements.  


