# Depression Assistant Chatbot
---
In this project, I extend the implementation of a Tweet/Sentence Sentiment Classification (repository present in my profile) to a concept of "Depression Assistant Chatbot". In this concept, the chatbot asks the users how they are feeling and if what they write expresses sadness of anger then they are greeted with jokes until they feel better.

### Working
-----------
For this chatbot, I am using the same code that i used for the previous project Tweet Sentiment Classification. The only difference is that in this project, user is asked how he/she is feeling and depending on the response the sentiment of their response is judged using a single hidden layer neural network classifier. If the classification shows that response contained fear or anger then the user is offered by the software a joke and the chatbot again asks the user if they want to read another joke. And this process keeps happening until the user says No. After that the user is greeted goodbye and the chatbot closes.

