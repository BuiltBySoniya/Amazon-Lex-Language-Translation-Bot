# 🚀 Amazon Lex Language Translation Bot

### AI-Powered Multilingual Chatbot Using AWS Lex & Translate

## Short Description

Built an intelligent multilingual chatbot using **Amazon Lex**, **AWS Lambda**, and **Amazon Translate**. Users input text in one language, and the bot detects the intent and target language, translates the text in real time, and returns the translated output.

## 🛠️ AWS Services Used:

Amazon Lex,
AWS Lambda,
Amazon Translate,
AWS IAM,
Amazon CloudWatch,

## 🧰 Technical Tools:

Python,
AWS SDK (Boto3),
AWS CLI,
Visual Studio Code,

## 🧠 Skills Demonstrated:

Natural language processing with Lex,
Real-time translation workflows,
Serverless integration across AWS services,
Multi-language conversational design,

## 📋 Steps Performed

### Configure Lex Bot Framework:

Created a Lex bot with language locale and basic welcome prompt. Defined intents and sample utterances for translation requests (e.g., “Translate English to Spanish”).
Configured session attributes and a dialogue branch to capture source text and target language.

### Define Intents & Slots:

Added slots: `sourceText` (Text) and `targetLanguage` (String with enum values: Spanish, French, Japanese, etc.).
Specified slot prompts and validation logic in Lex to guide users through the translation workflow.

### Integrate Lambda for Fulfillment:

Developed a Python Lambda function (`translateHandler`) invoked on fulfillment.
Lambda uses Amazon Translate to translate `sourceText` into `targetLanguage`, builds a JSON response, and returns it to Lex for the chat interface.

### Deploy & Test Bot Conversations:

Configured Lex alias and published the bot.
Tested multilingual conversations via Lex console (English → Spanish, French → Japanese).
Validated expected responses, correct translations, and intent resolution across languages.

## ✅ Final Result:

Multilingual Translation Chatbot

## 💼 Business Implication:

This project showcases how conversational AI and AWS services can be combined to provide real-time translation capabilities at scale. Ideal for customer support, global chatbots, e-learning assistants, or any multilingual service scenario—reducing latency and bridging language barriers with cloud-native automation.
