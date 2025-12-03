Chatbot With Sentiment Analysis
Objective

The objective of this project is to build a chatbot that interacts with the user and performs sentiment analysis.
The chatbot analyzes:

Overall sentiment of the entire conversation (Tier 1 – Mandatory)

Sentiment of each individual user message (Tier 2 – Additional Credit)

Features :

1.Chatbot interaction with the user
2.Stores full conversation history
3.Statement-level sentiment analysis
4.Final conversation-level sentiment output
5.Implemented in Python (Google Colab)
6.Uses VADER Sentiment Analyzer

Technologies Used :

1.Python 3
2.Google Colab
3.vaderSentiment library

Sentiment Analysis Logic:

The VADER analyzer generates a compound sentiment score:

compound ≥ 0.05 → Positive
compound ≤ -0.05 → Negative

Otherwise → Neutral

Tier 1:
Conversation history is analyzed to produce the overall sentiment.
Tier 2:
Each message is analyzed individually and its sentiment is displayed immediately.

How to Run (Google Colab)

1.Open Google Colab
2.Create a new notebook
3.Install required library:
4.!pip install vaderSentiment
5.Paste the chatbot code into a cell
6.Run the code
7.Type messages → sentiment appears
8.Type bye to end the chat
9.Final overall sentiment is displayed



Name:Bibhu Prasad Nayak
Assignment: Chatbot With Sentiment Analysis
