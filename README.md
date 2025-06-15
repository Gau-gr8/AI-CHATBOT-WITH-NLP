# AI-CHATBOT-WITH-NLP

*COMPANY*: CODETECH IT SOLUTIONS

*NAME*: GAURI AGARWAL

*INTERN ID*: CT06DF709

*DOMAIN*: PYTHON PROGRAMMING

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTHOSH
                                          
*DESCRIPTION*:
The primary goal of this task is to create an intelligent system capable of understanding and responding to user queries in a natural, conversational manner. This project utilized the NLTK (Natural Language Toolkit) library in Python and was developed using Visual Studio Code (VS Code) as the integrated development environment (IDE).

TOOLS AND TECHNOLOGIES USED: 
1. PYTHON: For its simplicity, readability, and powerful libraries for NLP.
2. NLTK ( Natural Language Toolkit): For natural language processing tasks like tokenization, stemming, etc.
3. json: To load and read the intents.json file containing patterns and responses.
4. RANDOM: To randomly select responses from a given intent.
5. VISUAL STUDIO CODE IDE: Used for writing, testing, and debugging the code.

PROCESSES: 
1. CREATING A *intents.json* FILE:
   Define a structured set of intents (like greetings, goodbyes, etc.)
   Each intent includes:
   "tag": the category name
   "patterns": sample user inputs
   "responses": bot's replies
2. IMPORT REQUIRED LIBRARIES:
  Import NLTK modules: word_tokenize, PorterStemmer, etc.
  Load the intents.json file using Python’s json module.
3. PREPROCESSING OF DATA:
   Tokenize the sentences using nltk.word_tokenize().
   Apply stemming to reduce words to their root forms.
   Remove punctuation and convert all text to lowercase.
4. BUILD VOCABULARY AND TRAINING DATA:
   Create a list of all unique stemmed words (vocabulary).
   Convert each pattern into a bag-of-words vector.
   Tag each vector with its associated intent.
5. PREDICT USER INTENT:
   Preprocess user input in real-time.
   Convert it to a bag-of-words.
   Use the model to predict the best matching intent tag.
6. RESPOND TO USER:
   Match predicted intent to its tag in intents.json.
   Select a random response from the list of responses under that tag.
7. RUN CHATBOT LOOP:
   Take input from the user in a loop.
   Keep responding until the user types "quit" or similar.

APPLICATIONS:
1. CUSTOMER SUPPORT
2. EDUCATIONAL ASSISTANTS
3. HEALTHCARE SERVICES
4. E-COMMERCE
5. ENTERTAINMENTAND COMPANIONSHIP

OUTPUT:
![Image](https://github.com/user-attachments/assets/6f1bb5dd-719f-4357-99a0-d5e04c5619a1)

   
