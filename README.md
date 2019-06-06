# AI-ML Chatbot

**AIML** stands for Artificial Intelligence Markup Language. AIML is an XML based markup language meant to create an Artificial Intelligent applications. AIML makes it possible to create human interfaces while keeping the implementation simple to program, easy to understand and highly maintainable. 

AIML was developed by the Alicebot free software community and Dr. Richard S. Wallace during 1995-2000. 

AIML is used to create or customize Alicebot which is a chat-box application based on A.L.I.C.E. (Artificial Linguistic Internet Computer Entity) free software.

This is a practice repo where I have tried replicating [this](https://github.com/sohelamin/chatbot) project with some additional AI-ML files.

| Tags | Description |
| ----- | ---- |
| `<aiml>` | Defines the beginning and end of a AIML document. |
| `<category>` | Defines the unit of knowledge in Alicebot's knowledge base. |
| `<pattern>` | Defines the pattern to match what a user may input to an Alicebot. |
| `<template>` | Defines the response of an Alicebot to user's input. |
| `<star>` | Used to match wild card * character(s) in the <pattern> Tag. |
| `<srai>` | Multipurpose tag, used to call/match the other categories. |
| `<random>` | Used <random> to get random responses. |
| `<li>` | Used to represent multiple responses. |
| `<set>` | Used to set value in an AIML variable. |
| `<get>` | Used to get value stored in an AIML variable. |
| `<that>` | Used in AIML to respond based on the context. |
| `<topic>` | Used in AIML to store a context so that later conversation can be done based on that context. |
| `<think>` | Used in AIML to store a variable without notifying the user. |
| `<condition>` | Similar to switch statements in programming language. It helps ALICE to respond to matching input. |

### Requirements
    Python = 2.x.x
    Flask
    Aiml
    pip

## Installation

1. Clone and navigate to chatbot directory.

2. Install the required packages.
    ```bash
    pip install -r requirements.txt
    ```

3. Run the python server.
    ```bash
    python main.py
    ```
4. Open **http://127.0.0.1:5000** or **http://localhost:5000** in your browser.

5. You're done and let's chat with your Robot via browser.

## Screenshot




##### References
1. https://www.tutorialspoint.com/aiml/
2. https://www.devdungeon.com/content/ai-chat-bot-python-aiml

