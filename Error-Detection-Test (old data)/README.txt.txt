FILE BREAKDOWN:  

trainingtest (folder of pngs): 

- name-organized and compressed images for training data 
- three classifications: low pressure (clogged material), good (normal), and too close (scraps material)
- RGB channels

Dataset Preparation (notebook): 

- creates CSV 

test_data (CSV): 

- spreadsheet of pixels of trainingtest images to be read by model

Multiclassification Test (notebook): 

- loads csv data, trains model, and saves as h5

final_model.h5 (h5 saved model): 

- saved final model to be loaded for prediction-making

Load Multiclassification Model (notebook): 

- loads final_model.h5 and makes predictions 