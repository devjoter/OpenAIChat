Overview
OpenAIChat is a SwiftUI-based iOS application that allows users to interact with OpenAI's GPT-4 model through a chat interface. The app simulates a conversational assistant that responds to user inputs with intelligent and context-aware responses.

Features
User Input: Users can type messages into a text field and send them to the chat.Message length is decreased for 100 tokens.
Chat Responses: The app displays the responses from the GPT-4 model in the chat interface.
Error Handling: If the API request fails, the app informs the user by displaying an error message in the chat.
Prerequisites
Xcode 12 or later
Swift 5.3 or later
An OpenAI API key

How to Use
Open the App: Launch the app on your iOS device.
Send a Message: Type a message in the text field at the bottom of the screen and press the "Send" button.
View Responses: The response from the GPT-4 model will appear in the chat interface. If there is an error, an error message will be displayed.
Code Overview
ContentView.swift: Defines the main user interface, including the text field for user input and the chat display.

ChatViewModel.swift: Manages the state and business logic of the chat, including sending messages to the OpenAI API and handling responses.

APIService.swift: Handles network requests to the OpenAI API, sending user messages and receiving model responses.

ChatMessage.swift: Defines the data structure for chat messages.

Example Usage
Open the App: The app will greet you with "Hello, how can I help you today?".
Input a Message: Type "What is the weather like today?" in the text field and press "Send".
Receive a Response: The GPT-4 model will respond with a message like "I'm sorry, but I can't provide real-time weather updates."
Error Handling
If the app encounters an issue with the API, it will display "Request failed" in the chat.

License
This project is licensed under the MIT License. See the LICENSE file for details.


Source Code:
https://github.com/devjoter/OpenAIChat.git

