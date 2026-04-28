# Convolutional-Neural-Network-for-Orientation-Specific-Brain-Tumour-Classification
Comparing two CNNs for brain tumour classification from MRI scans, one uses an initial MRI orientation identification model with classified orientation fed into the CNN for higher accuracy.

## Data

The dataset used was a collection of 3064 MRI brain scans from 233 patients, with folders for 3 tumour types meningiomas, gliomas, and pituitary tumors.
Dataset can be found here: https://www.kaggle.com/datasets/denizkavi1/brain-tumor

## Report

A formal report detailing the theory, implementation, results, and conclusions is included here:  
 [`Sarah_Straw_CNN_report.pdf`](./images/CNN_Report.pdf)


---

## Output Plots

![Orientation Examples](image/orientation_examples.png)
> MRI scans and their model predicted orientation to validate the model.

![CNN Diagram part 1](image/CNN_diagram_part1.png)
> Diagram showing the first layers of the CNN with dimentions below.

![CNN Diagram part 2](image/CNN_1_part2.png)
> The three 'heads' of the CNN where the images orientation funnels it to a head.

![results](image/confusion_matrix.png)
> Matrix of the true and model predicted tumour type, perfect accuracy would be the diagonals at 100%.


