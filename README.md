# AI_PCB_Defect_Detection_Classification_System
This project demonstrates PCB defect detection using image processing techniques. It includes dataset inspection, image alignment and preprocessing, subtraction to generate defect difference maps, and Otsu’s thresholding with filtering to highlight defect regions for accurate analysis.

## Dataset Used
- **Dataset:** DeepPCB Dataset  
- **Input Images:**
  - Template image (defect-free PCB)
  - Test image (PCB with defects)

The dataset contains paired PCB images used to detect manufacturing defects through comparison.

---

## ⚙️ Tools & Technologies
- Python  
- OpenCV  
- NumPy  
- Matplotlib  
- Google Colab  

---

## 🔍 Process Explanation

### 1️⃣ Dataset Setup and Inspection
- Loaded the DeepPCB dataset  
- Verified image pairs (template and test)  
- Checked image dimensions and formats  

---

### 2️⃣ Image Preprocessing & Alignment
- Converted images to grayscale  
- Resized images if required  
- Ensured proper alignment between template and test images for accurate comparison  

Proper alignment is crucial to avoid false defect detection.

---

### 3️⃣ Image Subtraction
- Performed absolute difference between the template and test images  
- Generated a difference map highlighting possible defect regions  

This step helps isolate changes caused by defects.

---

### 4️⃣ Thresholding & Filtering
- Applied Otsu’s thresholding to segment defect areas  
- Used filtering techniques to remove noise and enhance defect regions  
- Generated a binary defect mask  

---

### 5️⃣ Result Visualization
Displayed:
- Original template image  
- Test image  
- Difference image  
- Final defect-highlighted output  

This helps visually validate the defect detection results.

---

## ✅ Results
- Accurate identification of defect regions  
- Clear difference maps highlighting defects  
- Clean binary masks after thresholding and filtering  

---

## 📌 Key Learnings
- Importance of dataset preparation and alignment  
- Understanding image subtraction for defect detection  
- Practical usage of thresholding techniques like Otsu’s method  
- Hands-on experience with real-world image processing workflows  

---

## 🚀 Future Scope
- Add bounding boxes around detected defects  
- Integrate deep learning models for improved accuracy  
- Automate defect classification  

---

## 🙌 Acknowledgement
This project was completed as part of the **Infosys Virtual Internship** learning program.
