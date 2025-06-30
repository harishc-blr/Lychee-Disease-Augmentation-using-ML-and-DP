# 🍃 Lychee Leaf Disease Classification Using Deep Learning

This project focuses on detecting and classifying lychee leaf diseases using deep learning models like **AlexNet**, **GoogleNet**, and **ResNet-18**. The dataset used is the **Lychee Disease Augmentation Dataset**, which includes various diseased and healthy lychee leaf images enhanced with augmentation techniques.

---

## 📁 Dataset

**Name:** Lychee Disease Augmentation Dataset  
**Classes:**  
- Healthy  
- Alternaria  
- Anthracnose  
- Bacterial Blight  
- Cercospora  

**Augmentations Applied:**  
- Rotation  
- Flipping  
- Scaling  
- Color Jitter  

Split:  
- **80%** Training  
- **20%** Testing

---

## 🎯 Objective

To classify lychee leaf diseases automatically using transfer learning on well-known CNN architectures to assist in precision agriculture.

---

## 🧠 Models Used

- **AlexNet**  
- **GoogleNet (Inception v1)**  
- **ResNet-18**

All models were trained using **transfer learning** with ImageNet pre-trained weights.

---

## ⚙️ Technical Details

- **Framework:** PyTorch / TensorFlow (customizable)
- **Input Size:**
  - AlexNet: 227x227
  - GoogleNet & ResNet-18: 224x224
- **Optimizer:** Adam / SGD  
- **Loss Function:** CrossEntropyLoss  
- **Epochs:** 100  
- **Batch Size:** 32  

---

## 📊 Evaluation Metrics

- Accuracy  
- Confusion Matrix  
- Precision, Recall, F1-Score  
- Loss vs Epoch Curve  
- Reliability Curve (Calibration Plot)

---

## ✅ Results

| Model       | Accuracy |
|-------------|----------|
| AlexNet     | ~80%     |
| GoogleNet   | ~95%     |
| ResNet-18   | ~97%     |

📌 **ResNet-18** achieved the best accuracy and robustness due to its residual learning capability.

---


## 📌 Conclusion

Deep learning models can effectively classify lychee leaf diseases. ResNet-18, in particular, shows promise for real-world deployment in smart farming tools and disease diagnosis apps.

---

## 📎 Future Work

- Deployment as a web or mobile app  
- Integration with drone-based data collection  
- Real-time disease prediction using edge devices

---

## 🙌 Acknowledgements

- Based on the Lychee Disease Augmentation Dataset  
- Pretrained models from torchvision / TensorFlow hub  

---

## 📬 Contact

**Harish C**  
📧 harishc.blr@gmail.com  
🌐 [www.harishc.online](http://www.harishc.online)  
📍 Bangalore, India
