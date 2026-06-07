# Interactive Rule-Based Chatbot

A flexible, rule-based text chatbot written in Python. This bot goes beyond rigid, exact-match replies by using keyword detection, varying its responses randomly to sound more human, retaining memory of your name, and interacting with real-world system data.

## Features

* **Keyword Matching:** Uses the `in` operator to find phrases within longer sentences, allowing for a more natural text flow (e.g., recognizing "how are you" inside "Hey bot, how are you today?").
* **Dynamic Responses:** Leverages Python's `random` module to select from a pool of responses so the conversation feels less mechanical.
* **Basic Memory State:** Captures your name during conversation and stores it in memory to use or recall later.
* **Live Data Integration:** Imports the native `datetime` library to check and output your computer's actual local system time.
* **Smart Fallbacks:** Includes a randomized fallback system to smoothly handle phrases or questions it hasn't been programmed to answer yet.

## Prerequisites

To run this chatbot, ensure you have Python 3 installed on your computer.
* Python 3.x (Available for download at [python.org](https://www.python.org/))

## How to Run the Chatbot

1. Save the upgraded chatbot code into a file named `chatbot.py`.
2. Open your terminal, command prompt, or the integrated terminal inside VS Code.
3. Navigate to the directory/folder where your `chatbot.py` file is saved.
4. Run the script using the following command:
```bash
   python chatbot.py
