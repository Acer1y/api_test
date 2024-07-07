This was a branch for testing a prompting format with ChatGPT and learning API consumption/communication, I never turned this into anything outside of a local page for testing purposes. Originally the idea was to integrate to Google's own Gemini service but I found that the functionality lacked features vs ChatGPT. 

GPT prompt in my app included chat history, making a proper text based game possible where it remembered up to a GPT limitation of prompts. The site is not active, but the code mainly remains intact, minus the keys. Because this was practice, I opted to use the request feature as I didn't know about fetch at the time. The inline script in the HTML takes the submitted text and feeds it to GPT, which in turn responds with the scenario in JSON. 

The response is then formatted to a readable format and inserted into the response block created in the HTML above the submit field. 
