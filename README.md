# Chatbot Projects

This repository contains two chatbot implementations: a simple general-purpose chatbot and a specialized college admission chatbot.

## 1. Simple Chatbot (BuddyBot)

BuddyBot is a basic chatbot implemented in Python. It can handle simple conversations, remember user information, and maintain context.

### Features:
- Greet users
- Answer basic questions
- Remember user names
- Maintain conversation context
- Ask follow-up questions
- Handle unknown inputs

### Usage:
```python
chatbot = BuddyBot()
user_id = 1
print(chatbot.greet(user_id))
print(chatbot.ask_question(user_id))
print(chatbot.register_user(user_id, "John"))
# Continue interaction...
print(chatbot.farewell(user_id))
```

## 2. College Admission Chatbot (AdmissionChatbot)

This chatbot is designed to assist prospective students with college admission inquiries. It provides information about various programs, requirements, deadlines, and more.

### Features:
- Program-specific information (Engineering, Business, Computer Science, Medicine, Law, Psychology, Arts)
- Admission requirements
- Application deadlines
- Course information
- Faculty details
- Application fees
- Natural language processing for better understanding of user queries
- Sentiment analysis to detect user frustration

### Usage:
```python
if __name__ == "__main__":
    chatbot = AdmissionChatbot()
    chatbot.start_conversation()
```

### Dependencies:
- NLTK
- TextBlob

## Getting Started

1. Clone this repository
2. Install the required dependencies:
   ```
   pip install nltk textblob
   ```
3. Run the desired chatbot script

## Contributing

Feel free to fork this repository and submit pull requests with improvements or additional features for either chatbot.

