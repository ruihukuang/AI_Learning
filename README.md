# AI_Learning

## foundation 

### lab 1  
Context:
Use gpt-4.1-nano to ask a simple math question. Then use gpt-4.1-mini to come up with a question about testing IQ and then use this model again to answer this questions.   
A simple math question from gpt-4.1-nano  
<img width="604" height="221" alt="image" src="https://github.com/user-attachments/assets/17482685-c804-4612-a1d3-0ad2698902d1" /> 
A question about testing IQ from gpt-4.1-mini  
<img width="842" height="266" alt="image" src="https://github.com/user-attachments/assets/ee315c3e-2863-4f45-a7ac-8e6105ce869a" />  
Answer this question from gpt-4.1-mini  
<img width="985" height="524" alt="image" src="https://github.com/user-attachments/assets/7f7447f4-633c-458a-afad-58d7e44bd9dd" />  
<img width="882" height="491" alt="image" src="https://github.com/user-attachments/assets/0f2b076f-f5c3-4ac3-a3ff-c19037fee23a" />  

### lab 2  
Context  
Use gpt-4o-mini to come up a question to evalute intelligence of a number of LLMs. Answers are provided by gpt-4o-mini,claude-3-7-sonnet-latest, gemini-2.0-flash,deepseek-chat and llama-3.3-70b-versatile . Then provide the question,responses from these LLMs without specifying model names and context for a model o3-mini acting as a judge to rank these models based on clarity and strength of argument related to responses. 

The question from gpt-4o-mini  
If you could redesign the ethical framework governing artificial intelligence, what fundamental principles would you prioritize, and how would you address potential conflicts between those principles in real-world applications?    
<img width="688" height="229" alt="image" src="https://github.com/user-attachments/assets/947771e4-7bc0-4c6b-9807-27ceb97be5d6" />  

Answers from gpt-4o-mini  
<img width="677" height="296" alt="image" src="https://github.com/user-attachments/assets/77cfea60-f1ec-41ca-bb0a-cef57cb7cc1a" />    
Answers from claude-3-7-sonnet-latest    
<img width="733" height="320" alt="image" src="https://github.com/user-attachments/assets/3cd14ead-bcd8-4ee6-965c-129c4be51439" />    
Answers from gemini-2.0-flash    
<img width="729" height="280" alt="image" src="https://github.com/user-attachments/assets/5ca741da-6d00-475f-ab58-3275e0b5707c" />    
Answers from deepseek-chat  
<img width="728" height="279" alt="image" src="https://github.com/user-attachments/assets/227f4b74-086f-4ed7-b28a-5c74b8d443d6" />    
Answers from llama-3.3-70b-versatile    
<img width="753" height="279" alt="image" src="https://github.com/user-attachments/assets/4a2a3922-c386-4ff9-ae6f-f1630e651fb9" />    
Ranking order   
<img width="611" height="284" alt="image" src="https://github.com/user-attachments/assets/72fcf47b-f98b-475c-b912-ff970a7b9c5e" />  

### lab 3  
Context  
I have my linkin profile pdf and a summary text file about myself. Use gpt-4o-mini for my chat box. This locally built chat box is to act as me and answer questions on my local website. The questions are related to Janice's career, background, skills and experience. If it doesn't know the answer, it could not answer. Then use gemini-2.0-flash to evaluate the answers from gpt-4o-mini. If the answers are acceptable, they will be shown in the chat box with updated version. If the answers are not acceptable, gpt-4o-mini will be used again to provide another answers.   
The chat box with gpt-4o-mini to provide answers      
<img width="1012" height="537" alt="image" src="https://github.com/user-attachments/assets/a4bd5a47-5e2a-4e7c-b93a-80fdb53f73c5" />    
The chat box with gemini-2.0-flash to evaluate answers and gpt-4o-mini to provide better answers with the approval from gemini-2.0-flash           
<img width="1127" height="542" alt="image" src="https://github.com/user-attachments/assets/4232698a-8cd7-49f2-b4e9-581df879c9e6" />  
<img width="2033" height="1000" alt="image" src="https://github.com/user-attachments/assets/c1c0a778-d446-49d4-b200-628b83bff350" />  
In addition, it could require gpt-4o-mini to answer a question in certain way like using pig latin. But the provided answers could not pass the evaluation of gemini-2.0-flash. Then gpt-4o-mini is reused to provide better answers in the chat box.  
<img width="2114" height="899" alt="image" src="https://github.com/user-attachments/assets/de12537c-f786-4598-a8c5-13994de2784e" />


### lab 4  
Context  
A locally built chat box was created to answer questions related to Janice's career, background, skills and experience. If questions could not be answered, a message will be sent to and saved in an app in pushover and I will be notified of these questions on my phone. if a users wants to leave contact details, a message will be sent to and saved in an app in pushover on my phone as well for a notification.    
In addition, a chat box was created in a private space in HuggingFace with the URL https://huggingface.co/spaces/Janice-kuang87/career_conversation_. This chat box serves the same functions as a locally built chat box to notify me of unanswerable questions and user contact details.  
Unanswerable questions that will be sent to my phone from a chat box  
<img width="998" height="509" alt="image" src="https://github.com/user-attachments/assets/fad35308-a4bf-4208-9268-7d252b611c20" />   
User contact details that will be sent to my phone from a chat box   
<img width="1027" height="500" alt="image" src="https://github.com/user-attachments/assets/a8cc91d5-7fac-4672-a215-342b8368f33d" />  
A chat box in a private space in HuggingFace   
<img width="1857" height="854" alt="image" src="https://github.com/user-attachments/assets/ef5f3af7-669a-4545-89af-7797f036449e" />  




















