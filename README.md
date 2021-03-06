# HebbNet
An early simple artificial neural network is used for understand the training and working principles of neural networks. You can understand the working principle of the neural network according to the truth table of the two gates below.<br>

# Update History
Oct. 31 2018 - correct target calculation formula.

# Train
Input X1, X2 and Y(Target). Then click the "Train" button. The weights will be changed.<br>
Formula(target=y): new_weight[x] = old_weight[x] + input[x] × target


# Test
Just enter X1 and X2. Then click the "Test" button. The trained network will calculate the Y(target) based on input.

# Network Structure
![image](https://github.com/a2824256/HebbNet/blob/master/HebbNet.jpg)

# AND gate truth table
| X1    | X2    | Y     |
| ----- | ----- | ----- |
| 0     | 0     | 0     |
| 0     | 1     | 0     |
| 1     | 0     | 0     |
| 1     | 1     | 1     |

# OR gate truth table
| X1    | X2    | Y     |
| ----- | ----- | ----- |
| 0     | 0     | 0     |
| 0     | 1     | 1     |
| 1     | 0     | 1     |
| 1     | 1     | 1     |

# Software View (Trainning and testing the AND gate)
![image](https://github.com/a2824256/HebbNet/blob/master/View.png)
