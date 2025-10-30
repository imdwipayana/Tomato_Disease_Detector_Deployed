# 🍅 Tomato Disease Detector

Detect common tomato leaf diseases using a deep learning model built with **TensorFlow + MobileNetV2**.

This tool helps farmers, students, and researchers identify tomato plant health conditions from leaf images.

---

## 🌿 How to Use

1. Upload a photo of a **tomato leaf** (JPG/PNG format).
2. Wait a few seconds while the model analyzes the image.
3. The app will display:
   - The **predicted disease** (or “Healthy”),
   - **Confidence level**, and
   - **Prevention tips**.

---

## 🧠 Model Information

- **Architecture:** MobileNetV2 (Transfer Learning)
- **Framework:** TensorFlow / Keras
- **Input Size:** 224 × 224 pixels
- **Output Classes:**  
  - Bacterial Spot  
  - Early Blight  
  - Late Blight  
  - Leaf Mold  
  - Septoria Leaf Spot  
  - Spider Mites  
  - Target Spot  
  - Tomato Yellow Leaf Curl Virus  
  - Tomato Mosaic Virus  
  - Powdery Mildew  
  - Healthy  

The model was trained on tomato leaf datasets collected from open agricultural image repositories.

---

## ⚠️ Disclaimer

This application is for **educational and research purposes only**.  
It should **not** be used as a substitute for professional agricultural advice.  
Always consult an expert before applying treatments to crops.

---

## 📸 Example Images

You can test the app with your own tomato leaf photo, or use sample images from the `examples/` folder.

---

### 👨‍💻 Author

Developed by **Eka Dwipayana**  
🔗 [Run the model here](https://huggingface.co/spaces/imdwipayana/tomato-disease-detector)

🔗 [LinkedIn](https://www.linkedin.com/in/eka-dwipayana/)



---
