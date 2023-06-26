# Architected Material Lab: Multiclassification for 3D Printing Error Detection 

## Files in Repo

- FOLDER: **Error Detection** - (main folder with all relevant files for project)
    - NOTEBOOK: **Create CSV.ipynb** - (Create CSV to train model using images from a folder)
    - NOTEBOOK: **Create Random Test-Training Sets.ipynb** - (Randomly assign subsets of a data folder for training and test examples)
    - NOTEBOOK: **Live-Predictions.ipynb** - (Connect to camera and printer to make live predictions)
    - NOTEBOOK: **Load Multiclassification Model.ipynb** - (Load in selected model for manual predictions)
    - NOTEBOOK: **Multiclassification (3 Buckets Amount Extruded)** - (Train and save model to distinguish between Good, Overextrusion, Underextrusion)
    - NOTEBOOK: **Multiclassification (3 Buckets Layer One)** - (Train and save model to distinguish between Good, Overextrusion, Underextrusion when Printer prints 2-Dimensionally)
    - NOTEBOOK: **Multiclassification (5 Buckets Different Error Types)** - (Train + save model to distinguish between Good, Low/High Pressure, Nozzle Too Far/Close)
    - DATA FOLDER: **Raw Data** - (Uncompressed, raw images from camera, separated into time frames (May 30 morning + June 1 afternoon + June 15 afternoon))
    - DATA FOLDER: **Processed Data (5 Buckets)** - (Images of single extruded line prepared for model to distinguish between 5 error types)
    - DATA FOLDER: **Processed Data (3 Buckets)** - (Images of single extruded line prepared for model to distinguish between extrusion types (under, over, normal).)
    - DATA FOLDER: **Layer One Data (3 Buckets)** - (Images of single printed layer prepared for model to distinguish between extrusion types.)
    - DATA FOLDER: **Live Prediction Images** - (Images taken by camera while running live predictions)
    - DATA FOLDER: **Test Data (Different Batch)** - (Curated set of images from 2022 for data diversity)
    - **H5 FILES** - Saved models from Multiclassification Notebooks, to be loaded in for live predictions
    - **CSV FILES** -  Spreadsheets of images by LABEL and PIXELS to feed into model training 

- FOLDER: **CIFAR-10** - (multiclassification scripts to work on dataset CIFAR-10, aka non-printer data)

- FOLDER: **Error Detection Test (old data)** - (old version of multiclassification files used with curated data from 2022)

- NOTEBOOK: **Printer GUI.ipynb** - (m2py script used to connect computer to printer)

- TEXT FILE: **README.txt** - (raw notes)

## Notes and Updates
