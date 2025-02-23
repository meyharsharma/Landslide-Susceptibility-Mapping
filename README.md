Authors
Harshita Maurya
Priyangi Jain
Ananya Sharma
Meyhar Sharma
Muskan Nagdeo

Mentors
Dr. Rushina Singhi
Dr. Sunayana Sarkar
Prof. Prashant Dhamale

Overview
This study focuses on landslide susceptibility mapping in the Shillong Plateau, Meghalaya, using machine learning techniques. Given the region's geological complexity, high rainfall, and seismic activity, landslides pose a significant threat to life and infrastructure. To improve prediction accuracy, we applied Random Forest (RF), Support Vector Machines (SVM), and Convolutional Neural Networks (CNN) for classification and segmentation.

Objective
Develop a machine learning model to classify locations as landslide-prone or non-landslide-prone.
Compare Random Forest, SVM, and CNN to determine the most effective model for landslide prediction.
Provide an accurate landslide susceptibility map for informed decision-making and disaster management.

Methodology
Data Collection: 219 data points (99 landslide & 120 non-landslide points) were gathered from Bhukosh Geological Survey of India (GSI) and Google Earth.
Feature Engineering: Considered 10 factors, including elevation, slope, lithology, distance from faults, land cover, and vegetation index (VARI).

Model Implementation:
Random Forest & SVM: Used conditioning factors for classification.
CNN (U-Net architecture): Used Sentinel-2 satellite imagery for segmentation.
Evaluation Metrics: Accuracy, Precision, Recall, and F1 Score.

Results
Random Forest: Best performing model with 89% accuracy. Key influential factors: Slope, Distance from Faults, and VARI.
SVM (RBF Kernel + Bagging): 86.4% accuracy, slightly lower than RF but still effective.
CNN (U-Net): Achieved 98.54% accuracy, but its recall of 71.93% indicates a need for more feature inputs beyond just RGB bands.

Key Findings
RF outperformed SVM and CNN in classification accuracy for landslide susceptibility.
CNN provided spatial segmentation but lacked essential geological features, leading to moderate recall performance.
Slope, proximity to faults, and vegetation index (VARI) were critical factors in determining landslide susceptibility.

Limitations
Small dataset size; larger datasets could improve model performance.
CNN lacked multi-band satellite data, limiting predictive accuracy.
Changes in terrain over time were not accounted for in the model.

Future Scope
Integrate more geological and temporal data for improved predictions.
Develop time-series models to predict landslides dynamically.
Expand CNN analysis with additional spectral bands to enhance susceptibility mapping.

Acknowledgments
We thank the Department of Science and Technology (DST) and Dr. Sunayana Sarkar for their guidance and dataset contributions.
