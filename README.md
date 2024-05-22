# SMS Spam Detection System

## Background
Refactor an SMS text classification solution into a function that builds a linear Support Vector Classification (SVC) model. Deploy the model in a Gradio app to classify text messages as spam or not spam.

## Files
- Module 21 Challenge files.

## Setup
- Repository: `sms_spam_detector`
- Clone and push changes to GitHub or GitLab.

## Challenge Instructions

### SMS Classification Function
- Extract features from the text message column.
- Define the target from the "label" column.
- Split data into training and testing sets (test_size: 33%).
- Construct a pipeline with TfidfVectorizer and LinearSVC.
- Fit the model to the training data and return it.
- Load `SMSSpamCollection.csv` and apply the `sms_classification` function.

### SMS Prediction Function
- Predict the classification of new texts.
- Use conditional statements to determine if a message is "ham" or "spam".
- Return appropriate messages for "ham" and "spam" classifications.

### Gradio Interface Application
- Create a Gradio Interface with input and output textboxes.
- Label textboxes to guide users.
- Launch and share the application URL.
- Test the application with sample text messages.

## Requirements

### SMS Classification Function
- Set features to the text message column.
- Set target to the "label" column.
- Split data with a test size of 33%.
- Build and fit the model pipeline.
- Load and process `SMSSpamCollection.csv`.
- Store the result in the "text_clf" variable.

### SMS Prediction Function
- Create a variable for new text predictions.
- Implement conditional statements for "ham" or "spam".
- Return messages indicating spam status.

### Gradio Interface Application
- Construct a Gradio Interface with function, outputs, and inputs parameters.
- Ensure textboxes have descriptive labels.
- Provide a public URL for the application.
- Confirm the application functions correctly after user submissions.
