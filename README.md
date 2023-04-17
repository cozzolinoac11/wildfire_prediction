# Wildfire Prediction Dataset (Satellite Images)
### Satellite images of areas that previously experienced wildfires in Canada

## About Dataset
### Source
Refer to Canada's website for the original wildfires data:
Forest Fires - Open Government Portal
Original license for the data:
Creative Commons 4.0 Attribution (CC-BY) license – Quebec

### About Dataset
This dataset contains satellite images (350x350px) in 2 classes :
  - Wildfire : 22710 images
  - No wildfire : 20140 images
  
### How
Using Longitude and Latitude coordinates for each wildfire spot (> 0.01 acres burned) found on the dataset above we extracted satellite images of those areas using MapBox API to create a more convenient format of the dataset for deep learning and building a model that can predict whether an area is at risk of a wildfire or not
  
