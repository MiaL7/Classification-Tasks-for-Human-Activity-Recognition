# BIOSTAT-626 
# Midterm 1
Classification tasks for activity types using movement signals as features.

## Task Specification

https://github.com/xqwen/bios626/blob/main/README.md

>## Experiment design and data collection
>
>A group of volunteers, aged between 19 and 48, are recruited to participate in the experiment. They performed a protocol consisting of six activities: three static postures (standing, sitting, lying) and three dynamic activities (walking, walking downstairs, and walking upstairs). The experiment also recorded postural transitions that occurred between the static postures. These are: stand-to-sit, sit-to-stand, sit-to-lie, lie-to-sit, stand-to-lie, and lie-to-stand. All participants wore a smart device on the waist during the experiment. It captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz using the embedded accelerometer and gyroscope of the device. In this context, the activities are considered outcomes, and the signals measured by the smart device are considered features. 
>
>
>## Data pre-processing and description
>
>The sensor signals (accelerometer and gyroscope) were pre-processed by applying noise filters and then sampled in fixed-width sliding windows of 2.56 sec and 50% overlap (128 readings/window). The sensor acceleration signal, which has gravitational and body motion components, was separated using a Butterworth low-pass filter into body acceleration and gravity. The gravitational force is assumed to have only low-frequency components. Therefore a filter with a 0.3 Hz cutoff frequency was used. From each window, a vector of 561 features was obtained by calculating variables from the time and frequency domain. The details of the 561 features are described in files ``data_dictionary.txt`` and ``feature_info.txt``.
>
>
>
>## Data files 
>
>Two tab-delimited text files ```training_data.txt``` and ```test_data.txt``` are provided. The training data (labeled activity information included) should be used to construct and test your ML algorithms. Apply your algorithm to the test data (containing only feature information) and predict the activity corresponding to each time window.
>
>
>
>
>## Learning tasks
>
>1. Build a binary classifier to classify the activity of each time window into static (0) and dynamic (1).
>2. Build a refined multi-class classifier to classify walking (1), walking_upstairs (2), walking_downstairs (3), sitting (4), standing (5), lying (6), and static postural transition (7)

---------------------------------------------------------------
