# Diamond Similarity Prediction

**Goal**

The goal of the Diamond Similarity Prediction project is to develop a predictive model capable of estimating the similarity between diamonds based on various features. By leveraging machine learning techniques such as random forest classifier, k-means clustering, feature extraction, foreground extraction using GrabCut, and histogram intersection, the project aims to provide accurate predictions of diamond similarity. Through extensive analysis and evaluation, the resulting model aims to showcase superior predictive accuracy.

**Functionality**

**Model Development**

  1. Random Forest Classifier: Utilized to classify diamonds based on their features and characteristics.
  2. K-Means Clustering: Employed to group diamonds with similar attributes into clusters for analysis.
  3. Feature Extraction: Extracted key features from diamond images and associated data to use as inputs for the model.
  4. Foreground Extraction using GrabCut: Used to segment diamond images and extract the foreground accurately.
  5. Histogram Intersection: Calculated histogram intersection for comparing color features of diamonds.
     
**Evaluation and Analysis**
  
  1. Proportion Difference within Clusters: Analyzed to understand the distribution and variation of diamond proportions within clusters.
  2. Euclidean Distance for HSV and LAB Values: Calculated to measure the color similarity between diamonds using different color spaces.
  3. Similarity Scores Generation: Generated similarity scores based on the model predictions and evaluation metrics.
     
**How to Use**

  1. Navigate to User Interface: Access the user interface of the Diamond Similarity Prediction.
  2. Enter Diamond Code:Input the unique diamond code or identifier associated with the diamond you wish to analyze for similarity.
  3. Provide Diamond Attributes: Enter the shape, color, and scale of the diamond as additional attributes to refine the similarity search.
  4. Upload Diamond Image: Select and upload an image of the diamond to the system.
  5. System Processing: Upon upload, the system filters diamonds based on the provided attributes and preprocesses the uploaded image using OpenCV for analysis.
  6. Predict Similarity Score: The predictive model analyzes the extracted features and applies machine learning algorithms to predict the similarity score between the uploaded diamond and others in the database. The similarity score indicates the degree of resemblance or similarity between the uploaded diamond and others in terms of their features and characteristics.
  7. View Results: The system displays diamonds with similar scores, indicating the degree of similarity to the uploaded diamond. Users can review the list of similar diamonds along with their respective similarity scores to make informed decisions regarding diamond selection or comparison.

**Click on the image below to see the video:**

[![Diamond_Similarity_Prediction](http://img.youtube.com/vi/6rrJeIMjGw4/0.jpg)](http://www.youtube.com/watch?v=6rrJeIMjGw4 "Diamond_Similarity_Prediction") 
