Total Data: 

Collected May 30 (morning) + June 1 (afternoon)

Error Types: 

- Close (count: 683, label: too little extruded, description: nozzle too far down, structural difference)

- Far (count: 696, label: too much extruded, description: nozzle too far up, structural difference)

- HighP (count: 686, label: too much extruded, description: high pressure, liquidy)

- LowP (count: 724, label: too much extruded, description: low pressure, nozzle clogged)

- Good (count: 671, just right, description: printer works yay)


Traning Set: 

- C: 550
- F: 550
- H: 550
- L: 550
- G: 550
Total: 2750

Test Set: 

- C: 110
- F: 110
- H: 110
- L: 110
- G: 110
Total: 550

Manual Predictions (Extra)

- C: 23
- F: 36
- H: 26
- L: 64
- G: 11
Total: 160


Categorized Data (To Balance Extrusion Types)

- Underextruded (count: 550/110, description: C + L)
- Good (count: 550/110, description: G)  
- Overextruded (count: 550/110, description: H + F)
Total: 1650/330


Next Steps

- Correlation/cross Verification (CS227) - this week 
- Randomly assign test/train data (smaller subsets of both - DONE) 
- Collect new group of images (different batch of images as test data and check accuracy) - this week
- GCode
- Real-time predictions (***)


After implementing random assignment of test/training data: 

3 bucket accuracy: 
- 1. 99.091
- 2. 98.611
- 3. 99.213

5 bucket accuracy: 
- 1. 99.273



First Layer Error Prediction Model: 

Raw Data: (June 15)

Underextruded: (low pressure: 709, too close: 668)
Good: (726)
Overextruded: (high pressure: 559, too far: 640)

Prepared Data: 

Underextruded: (low pressure: 100 + 550, too close: 100 + 550) = 1300
Good: (580 + 720) = 1300
Overextruded: (high pressure: 100 + 550, too far: 100 + 550) = 1300


