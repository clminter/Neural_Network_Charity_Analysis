# Neural_Network_Charity_Analysis

## Overview
Develop a binary classifier that is capable of predicting whether charitable applicants will be successful if funded by Alphabet Soup using the following process:
- Preprocessing Data for a Neural Network Model
- Compile, Train, and Evaluate the Model
- Optimize the Model

## Results
### Preprocessing
Determine unique values per column:

![image](https://user-images.githubusercontent.com/81878169/132957387-88224ba8-f834-4f87-bb82-0c27ca370954.png)

Visualization and binning of data:

![image](https://user-images.githubusercontent.com/81878169/132957432-2bf9b31c-177d-459f-a5f4-5f6f902c8080.png)

OneHotEncoding:

![image](https://user-images.githubusercontent.com/81878169/132957565-93b0844a-0cea-4d06-a864-5c06e191ecc7.png)

Data is split into feature and target arrays; Data is scaled using the StandardScaler:

![image](https://user-images.githubusercontent.com/81878169/132957616-d590bf89-96d0-4410-987f-b81502b798b1.png)

### Compile, Train, and Evaluate the Model
Define model, define features, layers and nodes:

![image](https://user-images.githubusercontent.com/81878169/132957717-39373e7d-a725-42e4-b34d-8951dfb44b7e.png)

Compile the Model:

![image](https://user-images.githubusercontent.com/81878169/132957744-8dc2ddce-ad3b-4e29-9eb4-9fed1a0e1ed7.png)

Train and Evaluate the Model:

![image](https://user-images.githubusercontent.com/81878169/132957767-a5a8566e-d78d-4fb1-9860-61b0f0ef2f84.png)

### Optimize the Model
Dropping additional columns:

![image](https://user-images.githubusercontent.com/81878169/132957838-4b26a8ef-16cd-4f9f-91be-e52d1988e228.png)

Increase the threshold for class type from 500 to 700:

![image](https://user-images.githubusercontent.com/81878169/132957877-0960353d-39c3-46aa-bfbc-b2e1d765188f.png)


## Summary
