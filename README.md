## Nepali Handwritten Character Recognition with Deep Learning

### Overview 🎉
This project focuses on image classification using the Devanagari Handwritten Character Dataset (DHCD) for Nepali characters. Leveraging a pretrained ResNet model, the goal is to achieve accurate character recognition.

---

### Project Highlights 🚀
- Utilizes deep learning techniques for image classification.
- Training is performed on the DHCD (Nepali) dataset.
- Fine-tunes the ResNet model to improve its recognition capabilities.
- The model is designed to recognize handwritten Nepali characters.

---

###  Tools: PyTorch, Python

---

 📖 Dataset used in this project can be found on [DHCD](https://archive.ics.uci.edu/dataset/389/devanagari+handwritten+character+dataset) 

---

📜 ResNet101 undergoes transfer learning for the image classification process.
- Fine-tuning of ResNet101 is performed for the image classification task, following are the results after 5 epochs:
    - Test Accuracy Score: 0.9922
    - Train Accuracy Score: 0.8265
  
---

### ⬛ Raw Images. 
<picture>
  <img src="https://github.com/utsavbhattarai/NepaliCharClassification/blob/main/images/raw.png" width="300" height="200">
</picture>

<picture>  
  <img src="https://github.com/utsavbhattarai/NepaliCharClassification/blob/main/images/raw1.png" width="300" height="200">
</picture>


--- 
### ⬛ Model visualization - Predictions:
<picture>
  <img src="https://github.com/utsavbhattarai/NepaliCharClassification/blob/main/images/mv.png" width="300" height="600">
</picture>

<picture>
  <img src="https://github.com/utsavbhattarai/NepaliCharClassification/blob/main/images/mv1.png" width="300" height="600">
</picture>

---

### 📖 Sample List of Confused Character:
Most Confused Character Pairs:
- character_14_dhaa misclassified as character_18_da: 12 times
- character_23_ba misclassified as character_29_waw: 7 times
- character_29_waw misclassified as character_16_tabala: 6 times
- character_17_tha misclassified as character_26_yaw: 4 times
- character_4_gha misclassified as character_21_pa: 3 times
- digit_6 misclassified as digit_3: 3 times
- character_11_taamatar misclassified as character_16_tabala: 2 times
- character_12_thaa misclassified as character_11_taamatar: 2 times
- character_17_tha misclassified as character_4_gha: 2 times
- character_18_da misclassified as character_14_dhaa: 2 times
- character_19_dha misclassified as character_17_tha: 2 times
- character_24_bha misclassified as character_10_yna: 2 times
- character_2_kha misclassified as character_32_patalosaw: 2 times
- character_33_ha misclassified as character_13_daa: 2 times
- character_35_tra misclassified as character_23_ba: 2 times
- character_5_kna misclassified as character_13_daa: 2 times
- digit_3 misclassified as digit_6: 2 times
- digit_5 misclassified as character_27_ra: 2 times
- character_10_yna misclassified as character_8_ja: 1 times
- character_11_taamatar misclassified as character_13_daa: 1 times

---

### ⬛ Confusion Matrix diagram: 
<img src="https://github.com/utsavbhattarai/NepaliCharClassification/blob/main/images/cm.png" width="600" height="600">

---

