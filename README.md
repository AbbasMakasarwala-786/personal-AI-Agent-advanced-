# personal-AI-Agent 
This is a personal AI agent that can automate your daily task like sending tweets creating documents,Summarizing Emails,doing research and much more  

This code in langchain and langgraph is a personalized AI Agent that can help you in your tasks.

This Notebook has the Agetnic AI workflow whihc can perform several tasks such as:
1. `Enhancer`: Use prompt enhancer as the first preference, to Focuse on clarifying vague or incomplete user queries, improving their quality, and ensuring they are well-defined before further processing.
   
3. `Researcher`: Specializes in gathering information.
   
5. `research_paper_node`: this node helps to gather information about a research paper.
   
7. `Coder`: Handles technical tasks related to caluclation, coding, data analysis, and problem-solving, ensuring the correct implementation of solutions.
   
9. `Email Summariser`: this nod is responsible to get emails of the user and summarise them.
    
11. `document_create_node`: this node on its on do  research based on specific informations and then create an docs and give user the link
    
13. `tweeter node`: This node can do research for you and geneate automatic tweets based upon your requierements for you so you can go hands free
    
15. `slack Summarizer`: This node summarizes all your slack messages for you so you don't need to read each individually.


The Main `Supervisor Node` here is reponsible to delegate task to lower nodes based on user queries.

<img src=https://github.com/AbbasMakasarwala-786/personal-AI-Agent-advanced-/blob/main/8e611e3f-7f44-401b-af36-0e7da40c2164.png></img>

After cloning this repository 
run the requirements.txt file using:`pip install -r requirements.txt`

Then go to https://console.cloud.google.com/ and create two api's:
1. Create Creadentials for OAuth2.0 --> Enable Gmail API and add the contents of gmails API to credentials.json file
2. Create Credentials for services --> Enable Google Docs and Google Drive API'S download the contents and add to services.json file

Finally Add your Groq API key from https://groq.com/ and add it to your `.env' file 

After this you will be ready to Automate your Personal Work

