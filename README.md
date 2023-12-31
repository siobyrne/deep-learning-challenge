# deep-learning-challenge
This project uses deep learning neural networks to select funding applicants with the highest chances of success for a fictional non-profit. 

## Code Notes
PNG files of all plots can be found in the images folder. Checkpoint files are located in the checkpoints folder.

## Analysis
In the original model, accuracy was 0.73 and loss was 0.56. 

By utilizing the names of the applicants in the analysis (the original model removed the EIN and name data, the optimized model removed EIN only) and adjusting the classifications to 500 (down from 1000 in the original model) and number of epochs to 50 (down from 100 in the original model), we were able to achieve accuracy of 0.79 and loss of 0.45, within the target range of greater than 0.75 and less than 0.45, respectively. 

## Charts

![Loss Original](images/loss-original.png)

_Loss Original_

![Loss Optimized](images/loss-optimized.png)

_Loss Optimized_

![Accuracy Original](images/accuracy-original.png)

_Accuracy Original_

![Accuracy Optimized](images/accuracy-optimized.png)

_Accuracy Optimized_