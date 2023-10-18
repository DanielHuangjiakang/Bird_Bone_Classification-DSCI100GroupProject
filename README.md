# Bird Bone Classification: Distinguishing Terrestrial and Flying Birds Based on Skeletal Structure

## Overview:
This repository contains a classification model that identifies birds as either terrestrial or flying based on their skeletal structure.

## Key Findings:
- Model accuracy: ~85.5% on the testing dataset.
- TPR for flying birds: 86.4%
- TNR for terrestrial birds: 82.4%

## Dataset:
Measurements from 420 bird skeletons sourced from the National History Museum of Los Angeles County.

## Methodology:
1. **Data Preprocessing:** 
   - Standardization of predictors.
   - 25/75 split for testing and training.
   
2. **Modeling:**
   - K-Nearest-Neighbour classification.
   - K value: 3.

3. **Features:** 
   - Wing length (ulna and humerus).
   - Leg length (tarsus, tibiotarsus, femur).

## Impact:
A benchmark for researchers to classify birds by bone structure.

## Future Directions:
- Explore wing-to-leg length ratio and bird body mass.
- Consider bone diameter or density.
- Examine individual bone lengths.

## Contributors:
- Jiakang Huang

