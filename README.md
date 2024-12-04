**Features**
Intent Recognition: Uses a trained neural network to classify user input into predefined categories.
Customizable Responses: Offers flexibility to add new intents and responses via a JSON file.
Interactive Chat: Real-time interaction with users, offering helpful and context-aware responses.
Error Handling: Returns a default response when user input is ambiguous or not recognized.

**Technologies Used**

Programming Language: Python
Libraries:
NLTK: Tokenization and Lemmatization
TensorFlow: Building and training the neural network
NumPy: Data manipulation and processing
JSON: Storing intents and responses
Machine Learning: Dense neural network for intent classification

**Example Usage**

User Input: "Hi"
ChatBot Response: "Hello! How can I assist you today?"

User Input: "I forgot my password"
ChatBot Response: "Follow these steps: Click on 'Forgot Password,' enter your email, and follow the instructions to reset your password."

**Customization**
Add New Intents:
Update the intents.json file with new tags, patterns, and responses.
**Train the Model:**
Retrain the model by running the script to include the new intents.
Contributions
Feel free to contribute by submitting issues or pull requests to enhance the chatbot's functionality or performance.
