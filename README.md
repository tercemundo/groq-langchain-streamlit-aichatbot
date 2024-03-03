# March 3rd Update! "One-Click Installation and Set Up of Groq and Streamlit on Github Codespaces" 

I updated the original code (worked perfectly locally) that I forked from the cool dev at https://github.com/definitive-io/ in order to run Groq and the Streamlit App front end on Github CodeSpaces https://github.com/codespaces.  

For the apps code to run on Github Codespaces I created two new folders and two new files.  

One folder is named .devcontainer and contains a devcontainer.json file and the other folder is named .streamlit and contains a config.toml file.  

# Here are the beginner friendly steps for you to get up and running for free in the cloud. 

1.  Create or Login to your https://github.com/ account.  

2.  Right click on your mouse and COPY repo:themindfuldude/groq-langchain-aichatbot

3.  Next go to the top right of your Github Repository and PASTE repo:themindfuldude/groq-langchain-aichatbot in the Type / to search box.
  
4.  Press Enter on your keyboard and You will now see the repo:themindfuldude/groq-langchain-aichatbot as a selection choice.
   
5.  Click on the Repository link which will take you to my groq-langchain-aichatbot repository (while still keeping you siged in to yours-You should see your profile image if you added one on the top right corner of the page) .
 
7.  Go to the top right and click on the button that says "Fork" and then click on/select the + Create a new fork which will open up a new window in your Github repository. 

8.  Give your repository a name or keep the name that is already there, and then click save.  You are ready to Launch and Test  Groq and Streamlit and Github Codespaces.
   
9.  Go to the (near) Top right and click on the GREEN BUTTON that says CODE and select Codespaces.  This will lanuch your Github Codespaces Visual Studio Code Editor window and your free Codespaces server.
    
10. In your Terminal Window of your Codespaces Visual Studio Code Editor Type the following command and press enter: streamlit run app.py

11. A small browser Window will open on the top right side of your Codespaces Visual Studio Code Editor.
    
12. Click on the small browsers Launch in Your Browser Button and you are ready to begin using Groq!  

I Love Github Codespaces, Groq and Streamlit!  Amazing Products...Enjoy


(WILL REPLACE THIS) ![1 groq conversational chatbot](https://github.com/themindfuldude/groq-langchain-aichatbot/assets/130063458/0a6f2bac-ba17-429b-b773-dc0561df776f)


(WILL REPLACE THIS) (https://www.youtube.com/watch?v=Hc79sDi3f0U "Original")    // Video Link

# Groq LangChain Conversational Chatbot

This repository contains a Streamlit application that allows users to interact with a conversational chatbot powered by the LangChain API. The application uses the Groq API to generate responses and maintains a history of the conversation to provide context for the chatbot's responses.

## Features

- **Conversational Interface**: The application provides a conversational interface where users can ask questions or make statements, and the chatbot responds accordingly.

- **Contextual Responses**: The application maintains a history of the conversation, which is used to provide context for the chatbot's responses.

- **LangChain Integration**: The chatbot is powered by the LangChain API, which uses advanced natural language processing techniques to generate human-like responses.

## Usage

To use this application, you need to have Streamlit and the other required Python libraries installed. You also need to have a Groq API key, which you can obtain by signing up on the Groq website.

Once you have the necessary requirements, you can run the application by executing the script with Streamlit:

```shell
streamlit run app.py
```

This will start the Streamlit server and open the application in your web browser. You can then interact with the chatbot, and the application will generate responses based on the history of the conversation.

#betterongroq
