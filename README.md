The problem is approached as a regression problem.
The database consists of voice measurements of 42 individuals with Parkinson's disease in the initial phase, collected over a period of 6 months using a remote monitoring device.
The columns in the matrix contain data such as age, gender, time interval of data collection, and 16 voice measurements. The split between "train" and "test" is 75-25, and Mean Squared Error (MSE) is used as the performance metric.
In each case below, I varied the learning rate and the number of neurons on the hidden layers. I considered cases where the number of neurons on a layer is equal to or half of that of the previous layer, each with learning rates of 0.1 and 0.01.
