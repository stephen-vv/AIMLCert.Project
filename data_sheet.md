# Datasheet

## Motivation

The dataset is created to try and find a connection between passenger information and whether or not the passenger was likely to have survived based on some information of the passenger. The dataset is from kaggle.com
 
## Composition

- Each instance in the dataset represents a passenger onboard the Titanic
- There are 891 instances in the training set and 418 in the testing dataset.
- There are some missing datapoints that have been replaced with predicted data using median values from the dataset
- The dataset contains no confidential information, all information is public.


## Collection process

- The data was collected from the Titanic's passenger manifests.
- The dataset attempts to include all passengers, so no sampling strategy was used.
- The data is from the maiden voyage of the Titanic, which sank on April 15, 1912.

## Preprocessing/cleaning/labelling

- Preprocessing included changed male and female to 0 and 1, removing NaN entries and replacing with median values, and changing the embarked label to map to numeric values. The raw data is available and the script performs the processing.

## Uses

- The dataset could be used for many other modelling tasks including statistical analysis, classification algorithms or exploratory data analysis.
- The dataset should not be used for applications that are intended to be used with real time or personal data, as it is a historical dataset.

## Distribution

- The dataset is freely available on Kaggle
- The dataset is under Kaggles terms of use which includes for educational and non-commercial use.

## Maintenance

- The dataset is maintained by Kaggle

