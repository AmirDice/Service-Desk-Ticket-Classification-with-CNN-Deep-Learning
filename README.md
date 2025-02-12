# Service-Desk-Ticket-Classification-with-CNN-Deep-Learning
![servicedesk](https://github.com/user-attachments/assets/674e9c66-2929-4702-b200-6e0143261bde)

## Project Description
Effective management of service desk tickets is essential for maintaining customer satisfaction. This project utilizes deep learning to develop a reliable and precise classifier that automatically categorizes incoming tickets into predefined groups, optimizing service desk operations.

## Project Goal and Steps
Develop a CNN-based classifier to categorize service desk tickets and enhance customer service efficiency.  

- Construct a CNN model with an embedding layer, a 1D convolution layer, and a linear layer.  
- Train the model on `train_data` using an appropriate optimizer, limiting training to 3 epochs.  
- Evaluate the model on `test_data`, storing the predictions in a list named `predictions`.  
- Compute accuracy, per-class precision, and recall on `test_data`, saving them as variables: `accuracy`, `precision`, and `recall`, with `precision` and `recall` stored as lists.
