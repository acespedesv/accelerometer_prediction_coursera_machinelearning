# accelerometer_prediction_coursera_machinelearning

In this project, I try to create and test a prediction model for classes based on accelerometer data.

First, I read 2 files with information of people accelerometers. The first file contains information for training data and the second file contains information for testing.

The training data is divided in two parts (training the model - 80%, and validation - 20%)

The models used in this project are classification trees and random forest.

The confussion matrix of both models shows that random forest has higher accurancy. Therefore, I select random forest for the testing phase.

In the testing part the second file was used. This file contained 20 samples.

It is important, to say that the files were cleaned. That meand that non - significant columns were removed.
