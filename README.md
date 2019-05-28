# CONTENT ASSETS

### Table of Contents
* [Description](#description)
* [AIML files](#aiml-files)
* [Dialog templates](#dialog-templates)

## Description
The content assets in this repository are meant to help you get started building your Inbenta Chatbot.

## AIML files
AIML stands for Artificial Intelligence Markup Language. It is a XML-based dialect used to build natural language interactions. AIML is intended for handling off-topic conversations, its limited scalability being constrained by how much a human can teach the engine (as opposed to Inbenta's semantic engine).

In this repository you can find the following AIML files:

* about_bot_en.aiml: Information about the bot (name, age, etc.)
* about_human_en.aiml: Bot responds to and captures information about the user (name, age, etc.)
* american_actors_en.aiml: Information about American actors
* bot_variables_en.aiml: Responses that contain Chatbot Personality variables
* cleaning_complete_en.aiml: Removes part of the user utterance that is not relevant
* cleaning_partial_en.aiml: Removes part of the user utterance that is not relevant
* cleaning_past_reduction_en.aiml: Simplifies compound verbs so they can be easily recognized
* currencies_capitals_history_en.aiml: Information about currencies, capitals, and history
* films_en.aiml: Information about films
* functional_split_en.aiml: Splits user utterances to answer with two or more different templates 
* music_bands_en.aiml: Information about music and bands
* Negative_Sentiment_Detection.aiml: Basic negative sentiment detection
* politeness_en.aiml: Bot answers with greetings, and other politeness utterances
* Positive_Sentiment_Detection.aiml: Basic positive sentiment detection
* practical_info_en.aiml: Information about current date and time
* speech_fillers_en.aiml: Bot responds to users' speech fillers (like "me too", "are you sure?", etc.)
* stories_jokes_en.aiml: Bot answers with random stories and jokes
* yes_no_patterns_en.aiml: Bot responses to simple yes/no user inputs

You can find more information about AIML files in our [Help Center](https://help.inbenta.io/en/chatbot/knowledge/aiml/).

## Dialog templates
The dialog templates are a set of sample dialogs (in JSON format) that you can upload to your Inbenta instance to easily get started with our Dialog Manager.
You can find more information about the Dialog Manager in our [Help Center](https://help.inbenta.io/en/chatbot/knowledge/dialog-manager/).
