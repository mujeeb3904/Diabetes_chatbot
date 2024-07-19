# Diabetes Chatbot

## Project Description

The Diabetes Chatbot is an AI-driven tool designed to assist individuals with diabetes management. This chatbot provides users with personalized information and guidance to help manage their condition effectively.

### Features

- **Symptom Checker:** Assists users in identifying symptoms and suggests possible actions.
- **Dietary Advice:** Recommends meal plans and tips for maintaining a healthy diet.
- **Exercise Recommendations:** Suggests suitable exercises based on user input.
- **Medication Reminders:** Helps users keep track of their medication schedules.
- **FAQs:** Provides answers to common questions about diabetes management.

### Technologies Used

- **Python:** Main programming language.
- **Natural Language Processing (NLP):** For understanding and processing user queries.
- **Chainlit:** Web framework used for UI.
- 
### Model Information
Model Name: ``` Llama-2-7b-chat.ggmlv3.q4_0.bin```
Description: This is a pre-trained conversational model used to power the chatbot. It is optimized for dialogue and understanding user queries.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Mujeeb-Blouch/diabetes-chatbot.git
   ```
2. Navigate to the project directory:
   ```bash
   cd diabetes-chatbot
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4.Run the Scripts in Sequence:

a. Ingest Data:
First, execute ingest.py to process and prepare the data and store in vactor database.
```python ingest.py```

b. Train the Model:
Next, run model.py to train the chatbot model using the prepared data and train model on a custom dataset.
```chainlit run model.py -w```

c. Evaluate Accuracy:
Finally, execute accuracy.py to evaluate the model's performance and check its accuracy.
```python accuracy.py```

Run the Application:
After the model is trained and evaluated, start the chatbot application with:
```chainlit run model.py -w```

### Usage

Open a web browser and go to `http://localhost:5000` to start interacting with the chatbot.

### Contributing

Contributions are welcome! Please open issues or submit pull requests for improvements.

### License

This project is licensed under the MIT License.
