# Mayo Clinic - STRIP AI (Kaggle)

This repository I am going to write about how I used the data from "Mayo Clinic - STRIP AI" Kaggle challenge.

https://www.kaggle.com/competitions/mayo-clinic-strip-ai/overview

## Stroke:

### It happens in two ways:

- Ischemic Stroke: a blocked artery can cut off blood to an area of the brain

- Hemorrhagic Stroke: blood vessel can leak and burst, so the blood spills into the brain tissues or surrounding the brain.

### Who have a higher risk of stroke?

- Age of 55 and older

- African-American

- men

- have family history of stroke or heart-attack

- Additional Risk Factors:

- Being overweight

- Physicaly inactive

- Drinking Alcohol

- Recreational drug use

- Smoking

- High blood pressure

- High cholestrol

- Uncontrolled diabetes

- Heart disease

### Symptoms:

- Trouble speaking or comprehending

- Paralysis or numbness of the face, arm, leg

- Vision peoblems

- Trouble walking

- Loss of balance

- Severe headaches (sometimes in some types of stroke)



## Overview

The task in this challenge is to identify the origins of blood clot.


## Summary of Workdone

### Data:

- csv files:

  - train.csv: (754, 5), 17.9 kB (754 image_id, 634 patient_id, with 73% CE and 27% LAA labels)
  - test.csv: (4, 4), 124 B (4 image_id, 4 patient_id)
  - other.csv: (396, 5), 11.27 kB




### Training:

I couldn't finish training part because I couldn't download the image datas. The total size of the data is 395.36 GB.
I tried to take the data directly from kaggle. I installed Kaggle, macport, openslides, opendatasets, etc. and created API token on Kaggle to make it work, but I couldn't get it done.


### Future Work:

I would continue this competition, train the data, and calculate the accuracy of my training.

## Citations

https://www.mayoclinic.org/diseases-conditions/stroke/symptoms-causes/syc-20350113
