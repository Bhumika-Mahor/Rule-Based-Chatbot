# Rule-Based-Chatbot

### Description:- Build a simple rule-based chatbot that responds to specific keywords or phrases.

### Solution:- Implement a Python script that uses predefined rules to match user inputs and provide appropriate responses.

- We define a dictionary called rules where each key represents a keyword or phrase, and the associated value is a list of possible responses.
- The chatbot_response function takes user input, converts it to lowercase, and then checks if any of the keywords in the rules dictionary are present in the input. If a match is found, it selects a random response from the associated responses. If no match is found, it returns a random default response.
- We use a while loop to continuously accept user input until the user types "exit," at which point the chatbot says goodbye and the loop exits.
- Inside the loop, we call the chatbot_response function to generate a response based on the user's input and print the response.
