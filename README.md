# Facebook message data explorer (phân tích tin nhắn facebook tiếng Việt)
**Why**
Social media group, such as Messenger Group, is a rich ground for data mining to extract information about users interaction. Here I demonstrate some basic data exploration for a small group. For a large group with more data, a lot could be done, for example, finding cluster of users in more features space. 

**The Jupyter Notebook**

Load facebook data for a group chat (json files) into data frame, properly decode unicode Vietnamese, and explore the data (number of messages daily, monthly by senders, plot frequently used words and emoticons). 

**Frequency of interaction**
Number of messages, reactions by user, monthly average.
![](https://github.com/quynhneo/facebook-message-data-explorer/blob/master/daily.png)

**Interaction Matrix**

From the messages, you can extract an interaction matrix between users: Who is mostlikely to respond to whom in the group.
![](https://github.com/quynhneo/facebook-message-data-explorer/blob/master/interaction.png)

