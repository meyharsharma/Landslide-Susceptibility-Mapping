# Landslide Susceptibility Mapping Using Machine Learning in the Shillong Plateau, Meghalaya

## Authors  
- Harshita Maurya  
- Priyangi Jain  
- Ananya Sharma  
- Meyhar Sharma  
- Muskan Nagdeo  

## Mentors  
- Dr. Rushina Singhi  
- Dr. Sunayana Sarkar  
- Prof. Prashant Dhamale  

## Overview  
This study focuses on **landslide susceptibility mapping** in the **Shillong Plateau, Meghalaya**, using **machine learning techniques**. Given the region's **geological complexity, high rainfall, and seismic activity**, landslides pose a significant threat to life and infrastructure. To improve prediction accuracy, we applied **Random Forest (RF), Support Vector Machines (SVM), and Convolutional Neural Networks (CNN)** for classification and segmentation.

## Objective  
- Develop a machine learning model to classify locations as **landslide-prone** or **non-landslide-prone**.  
- Compare **Random Forest, SVM, and CNN** to determine the most effective model for landslide prediction.  
- Provide an accurate **landslide susceptibility map** for informed decision-making and disaster management.  

## Methodology  
### **Data Collection**  
- **219 data points** (99 landslide & 120 non-landslide points) were gathered from **Bhukosh Geological Survey of India (GSI)** and **Google Earth**.  
- **Feature Engineering**: Considered **10 key factors**, including:  
  - **Elevation, Slope, Lithology**  
  - **Distance from Faults, Land Cover, Watershed**  
  - **Vegetation Index (VARI), Distance from Shillong City**  

### **Model Implementation**  
- **Random Forest & SVM**: Used conditioning factors for classification.  
- **CNN (U-Net architecture)**: Used **Sentinel-2 satellite imagery** for image segmentation.  
- **Evaluation Metrics**: Accuracy, Precision, Recall, and F1 Score.  

## Results  
### **Random Forest (RF) - Best Performing Model**  
- **Test Accuracy**: **89%**  
- **Key Influencing Factors**: **Slope, Distance from Faults, VARI**  

### **Support Vector Machine (SVM)**  
- **Test Accuracy**: **86.4%**  
- **Kernel**: RBF (Radial Basis Function)  
- **Bagging Classifier Used for Performance Boost**  

### **Convolutional Neural Network (CNN - U-Net)**  
- **Accuracy**: **98.54%**, but **Recall: 71.93%**  
- **Landslide segmentation using RGB bands**  
- **Requires additional spectral bands for better performance**  

## Key Findings  
- **Random Forest outperformed SVM and CNN** in classification accuracy.  
- **CNN provided spatial segmentation** but lacked **geological and topographical inputs**, leading to moderate recall performance.  
- **Slope, proximity to faults, and vegetation index (VARI) were critical factors** in determining landslide susceptibility.  

## Limitations  
- **Dataset size is relatively small**; a larger dataset could improve model generalization.  
- **CNN model only used RGB bands**, limiting its predictive capability.  
- **Landslide susceptibility changes over time** were not considered.  

## Future Scope  
- **Integrate more geological and temporal data** for improved predictions.  
- **Develop time-series models** to predict landslides dynamically.  
- **Expand CNN analysis with additional spectral bands** to enhance susceptibility mapping.  

## Acknowledgments  
We thank the **Department of Science and Technology (DST)** and **Dr. Sunayana Sarkar** for their guidance and dataset contributions.

--- 
