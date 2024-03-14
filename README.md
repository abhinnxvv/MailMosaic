# MailMosaic
# Email Classification System

This repository contains code for building a system to classify emails into different departments using deep learning techniques and APIs for email retrieval and sending.

## Overview

The system utilizes various APIs including Gmail API, Microsoft Graph API, or IMAP/POP3 API to receive emails. After preprocessing the email data to remove irrelevant information, it is converted into a dataset format. The dataset is then tokenized and vectorized using BERT preprocessing and encoding techniques. Following this, the data undergoes further verification to ensure cleanliness. The preprocessed data is then used to train a deep learning model for email classification.

## Steps

### Dataset Preprocessing

1. **Import Data**: Initial step involves importing the dataset.
2. **Remove Irrelevant Data**: Eliminate data that doesn't correlate with the classified labels, ensuring only relevant information is retained.
3. **Fill Null Values**: Fill in any missing or null values within the dataset.
4. **Map Labels with Departments**: Associate labels with their corresponding departments or categories.
5. **Verify and Save Dataset**: Perform verification, correction, and observation on the dataset before saving it in CSV format.

### Data Analysis

1. **Visualize Labelwise Count**: Create visualizations to display the count of data for each label, aiding in understanding the distribution.
2. **Department Wise Piechart Distribution**: Generate pie charts illustrating the distribution of data across different departments.

### Model Building

1. **Train-Test Data Splitting**: Divide the dataset into training and testing subsets for model evaluation.
2. **Install BERT Pretrained Model**: Setup the BERT pretrained model, which will be utilized for text processing.
3. **Tokenization and Vectorization**: Process email messages by tokenizing and vectorizing them, assigning numerical values for classification.
4. **BERT Model Output**: Utilize the output of the BERT model through deep learning's initial layer.
5. **Sequential Deep Learning Layers**: Implement deep learning layers in a sequential manner for model training.
6. **Intermediate Layers**: Incorporate multiple intermediate layers using tensors to enhance the model's learning capabilities.
7. **Final Output Layer**: Use the final layer to produce the model's output, determining the classification of emails.

### Email Routing

Once emails are classified, they are tagged or labeled for a particular department. APIs are then used to send the emails to the specific departments accordingly.

## Dependencies

- Python 3.x
- TensorFlow
- BERT Pretrained Model
- APIs (Gmail API, Microsoft Graph API, IMAP/POP3 API)

## Usage

1. Clone the repository.
2. Install the required dependencies.
3. Follow the steps outlined in the code to preprocess data, analyze it, and build the classification model.
4. Ensure proper API configuration for email retrieval and sending.
5. Run the system to classify incoming emails into respective departments.

## Contributors

- [Abhinav Raja Raizada](https://github.com/yourusername)
- Aark Deep Sarkar
- Ishita Banerjee
- Aman Prasad Gupta
