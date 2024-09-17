
#### Checkout This artcile for detailed explanation of the code and terms used in the decision tree

https://medium.com/@shailendrap/anomaly-detection-in-unsupervised-data-using-decision-trees-ec4ae1338fde

### DataSet: 

- Region: We simulate data for four regions (North, South, East, and West).
- Temperature: We assume normal temperatures around 20°C with some variance.
- Rainfall: We assume average rainfall of around 50 mm, with variance to reflect normal weather patterns.
- Soil Moisture: This represents the average moisture in the soil, critical for wheat growth.
- Crop Yield: The yield (in kg per hectare) is normally distributed, but we’ll inject some anomalies by modifying temperature and rainfall values for certain regions.


In this dataset, some outliers or anomalies were introduced by artificially altering the temperature and rainfall values in specific regions. These anomalies simulate real-world scenarios such as unusual weather conditions that may affect wheat production.

### To evaluate the model, we can use several metrics:
1. Precision: The proportion of true anomalies among the detected anomalies.
2. Recall: The proportion of actual anomalies detected by the model.
3. F1-Score: The harmonic mean of precision and recall, giving a balanced measure of the model’s performance.
