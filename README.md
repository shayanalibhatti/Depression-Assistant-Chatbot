# Depression Assistant Chatbot
Mental issues trouble everyone at some point. AI can be helpful in these situations. In this project, I extend the implementation of a Tweet/Sentence Sentiment Classification (repository present in my profile) to a concept of "Depression Assistant Chatbot". In this concept, the chatbot asks the users how they are feeling and if what they write expresses sadness, fear or anger then they are greeted with jokes until they feel better.

### Working
For this chatbot, I am using the same code that i used for the previous project Tweet Sentiment Classification. The only difference is that in this project, user is asked how he/she is feeling and depending on the response the sentiment of their response is judged using a single hidden layer neural network classifier. If the classification shows that response contained fear or anger then the user is offered by the software a joke and the chatbot again asks the user if they want to read another joke. And this process keeps happening until the user says No. After that the user is greeted goodbye and the chatbot closes.

The file for jokes is in the repository with over 60 jokes.

### Results
Following image shows the working.
![image](https://user-images.githubusercontent.com/41015749/56463318-55ab1e00-6397-11e9-8fb2-c87affc16943.png)

### Conclusion
I believe that AI can be helpful in curing mental problems. This project uses a neural network based sentiment classifier and extends it to depression assistant entertaining the depressed with jokes. When used in right context it can be really helpful to people.
