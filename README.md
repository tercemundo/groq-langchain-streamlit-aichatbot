# Groq - Langchain - Streamlit AI Chatbot APP
I am not sponsored by Github. Groq, Langchain or Streamlist. I just love their incredible products - Gregory Kennedy

## March 2024 Update! "Easy Installation and Set Up of Groq API, Langchain and Streamlit App on Github Codespaces".  You will be able to Switch between and try out two of the best Open-Source AI models notably the Mixtral-8x7B-32768 MOE (Mixture of Experts) model  or the LLama2-70b-4096 model by Meta. 

I tweaked the original code (worked perfectly locally) that I forked from Definitive AI https://github.com/definitive-io/ in order to run Groq and the Streamlit App front end on Github CodeSpaces https://github.com/codespaces.  Definitive AI https://www.definitive.io/ was recently aquired (March 2024) by Groq to run Groq cloud https://wow.groq.com/news_press/groq-acquires-definitive-intelligence-to-launch-groqcloud/.

For the apps code to run properly on Github Codespaces I created two new folders and two new files.  

One folder is named .devcontainer and contains a devcontainer.json file and the other folder is named .streamlit and contains a config.toml file. The devcontainer.json file automates building a Docker container image that setsup and installs python 3.11, the VS Code extensions, the latest version of GIT and the Github Cli, all of the required app dependency packages, and most imporatntly automatically creates and activates a Conda virtual environment. 

## About Groq
![groqcloud_darkmode](https://github.com/themindfuldude/groq-langchain-streamlit-aichatbot/assets/130063458/e2b2b6ba-1583-41d2-93a0-0dfd1d19b6d6)

Groq® is a generative AI solutions company and the creator of the LPU™ Inference Engine, the fastest language processing accelerator on the market. It is architected from the ground up to achieve low latency, energy-efficient, and repeatable inference performance at 10x scale. Customers rely on the LPU Inference Engine as an end-to-end solution for running Large Language Models (LLMs) and other generative AI applications at 10x the speed. The LPU Inference Engine is available via the GroqCloud, an API that enables customers to purchase Tokens-as-a-Service for experimentation and production-ready applications. Jonathan Ross, inventor of the Google Tensor Processing Unit (TPU), founded Groq to preserve human agency while building the AI economy

- https://groq.com/

- https://console.groq.com/login - Get Your Free Groq API Key Here

- https://wow.groq.com/groq-labs/

## Mistral AI
Mixtral-8x7B-32768 MOE (Mixture of Experts)
https://mistral.ai/news/mixtral-of-experts/
https://mistral.ai/technology/#models

## Llama 2 70 
LLama2-70b-4096
https://ai.meta.com/research/publications/llama-2-open-foundation-and-fine-tuned-chat-models/

## Langchain
- https://www.langchain.com/

## Streamlit
- https://streamlit.io/  

## Here are the beginner friendly steps for you to get up and running for free in the cloud. 


##  Create or Login to your https://github.com/ account.


![1_groq conversational chatbot](https://github.com/themindfuldude/groq-langchain-aichatbot/assets/130063458/91226ca2-2394-4bfd-9c5c-0027edb6c3d4)

##

- Select/click on the right side icon in the text box below

              repo:themindfuldude/groq-langchain-streamlit-aichatbot

- Next go to the top right of your Github Repository and PASTE repo:themindfuldude/groq-langchain-aichatbot in the Type / to search box.
  
- Press Enter on your keyboard and You will now see the repo:themindfuldude/groq-langchain-aichatbot as a selection choice.
   
- Click on the Repository link which will take you to my groq-langchain-aichatbot repository (while still keeping you siged in to yours-You should see your profile image if you added one on the top right corner of the page) .

- Go to the top right and click on the button that says "Fork" and then click on/select the + Create a new fork which will open up a new window in your Github repository. 

- Give your repository a name or keep the name that is already there, and then click save.  You are ready to Launch and Test  Groq and Streamlit and Github Codespaces.
   
- Go to the (near) Top right and click on the GREEN BUTTON that says CODE and select Codespaces.  This will lanuch your Github Codespaces Visual Studio Code Editor window and your free Codespaces server.

- A small browser Window will open on the top right side of your Codespaces Visual Studio Code Editor.

- In your Terminal Window of your Codespaces Visual Studio Code Editor Type the command below and press enter:

               export GROQ_API_KEY=paste-your-groq-api-key-here

- API KEY EXAMPLE IS BELOW: GET YOUR FREE API KEY HERE: https://console.groq.com/login

               export GROQ_API_KEY=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

- NOTE THE API KEY ABOVE WILL NOT WORK FOR YOU AS I HAVE REVOKED IT.  NEVER REVEAL YOUR API KEY TO ANYONE!
    
- Click on the small browsers windows FULL SCRENN ICON, which wull open a full browser window and you are ready to begin using Groq, Langchain and Streamlit!  

# Groq-LangChain-Streamlit AI Chatbot

This repository contains a Streamlit application that allows users to interact with a conversational chatbot powered by the LangChain API. The application uses the Groq API to generate responses and maintains a history of the conversation to provide context for the chatbot's responses.

## Features

- **Conversational Interface**: The application provides a conversational interface where users can ask questions or make statements, and the chatbot responds accordingly.

- **Contextual Responses**: The application maintains a history of the conversation, which is used to provide context for the chatbot's responses.

- **LangChain Integration**: The chatbot is powered by the LangChain API, which uses advanced natural language processing techniques to generate human-like responses.
