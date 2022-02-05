
![Logo](https://chatgen.ai/wp-content/uploads/2021/02/chatbot-training.png)



# YouTube Link 

https://youtu.be/Narb_GPBWUg

# AI-ChatBot Using Python


This is My End semester Python project. In this project I build an AI Chatbot using the tensorflow and tflearn library I used the concepts of Natural Language Processing and Neural Network to build it. The intents file that we used for training is made by us.
# How it works ?
An untrained instance of ChatterBot starts off with no knowledge of how to communicate. Each time a user enters a statement, the library saves the text that they entered and the text that the statement was in response to. As ChatterBot receives more input the number of responses that it can reply and the accuracy of each response in relation to the input statement increase. The program selects the closest matching response by searching for the closest matching known statement that matches the input, it then returns the most likely response to that statement based on how frequently each response is issued by the people the bot communicates with.


## Dependencies

- pip3 install nltk
- pip3 install tensorflow==1.13.2
- pip3 install numpy
- pip3 install tflearn
- pip3 install random
- pip3 install json

## Installation

Create an environment

```bash
mkdir myproject
$ cd myproject
$ python3 -m venv venv
```
Activate it

```bash
venv/bin/activate  (Linux)
venv\Scripts\activate  (Window)
```
## Usage
Run
```bash
python train.py
```
After that Run
```bash
python chat.py
```
## Customize
Have a look at intents.json. You can customize it according to your own use case. Just define a new tag, possible patterns, and possible responses for the chat bot. You have to re-run the training whenever this file is modified.

```bash
{
  "intents": [
    {
      "tag": "greeting",
      "patterns": [
        "Hi",
        "Hey",
        "How are you",
        "Is anyone there?",
        "Hello"
             ],
      "responses": [
        "Hey :-) , This bot is for 'Cyber Awareness for Children'\n How can i help you? ",
        "Hi there, what can I do for you?",
        "Hi there, how can I help?"
      ]
    },
     {
     "tag": "Child Awareness",
     "patterns": [
     "About cyber children awareness",
     "information about cybersecurity for children",
     "What is cybersecurity for children?",
     "What is Cyber Child Awareness",
     "Cyber Children Awareness",
     "What is Cyber Children Awareness" 
     ],
     "responses": [
     "Cybersecurity for children has received much attention  and \n has become a rapidly growing topic due to the increased availability of the internet to children and \n their consequent exposure to various online risks"
     ]
     },
    {
    "tag": "Awareness",
    "patterns":  [
    "What is Cyber Awareness",
    "Cyber Awareness",
    "Cyber Adwareness",
    "Cyber Aware",
    "Awareness"
    ],
    "responses": [
    " Cyber awareness refers to the level of awareness and understanding end users  have about \n     cybersecurity best practices and the cyber threats that their networks or organizations face everyday "
    ]
   },
   {
   "tag": "Cyber Crime",
   "patterns": [
   "What is Cyber Crime?",
   "Cyber Crime",
   "About Cyber crime"
   ],
   "responses": [
   "cybercrime, also called computer crime, the use of a computer as an instrument to further illegal \n ends, such as committing fraud, trafficking in child pornography and intellectual property, stealing \n identities, or violating privacy."
   ]
   },
   {
   "tag": "Cyber Crime related children",
   "patterns": [
   "Cyber Crimes related to children",
   "Children cyber crime",
   "Types of cyber crimes related to children",
   "Types of cyber crimes"
   ],
   "responses": [
   "cybercrime against children including \n child pornography, \n cyber stalking, \n cyber bullying, \n defamation, \n grooming, \n hacking, \n identity theft, \n online child trafficking, \n online extortion, \n  sexual harassment, \n violation of privacy."
   ]
   }
   ```
   
## Created By

- [Dixit Panchal](https://www.linkedin.com/in/dixit-panchal-1b55911b6/)
- [Kartik Jivani](https://www.linkedin.com/in/kartik-jivani-a62078199/)
- [Shourya Bhat](https://www.linkedin.com/in/shourya-bhat-6161a41ab/)