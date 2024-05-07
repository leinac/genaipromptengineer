# genaipromptengineer
Problem statement
Use an LLM to determine the intent of the user based on their utterances.
We have been using Dialogflow CX to determine the intent of the user utterance and mapping
that to a &#39;tag&#39; that we can then use in our Webhook to execute the necessary logic. Now, we
want to see what the experience would be like, if we replaced Dialogflow CX with an LLM to do
the mapping of utterance to &#39;tag&#39; value. For eg.
Utterance = &#39;buy a computer&#39; OR &#39;purchase device&#39;
Tag = purchase_flow
Given the above, explain/build a Conversational agent to help a user place an order for a
computer (desktop or laptop). Your objective is to design a prompt (one or more) that would
allow the end user to have a guided conversation with an LLM, focus on determining the
appropriate tag and just explain what logic would be executed behind that tag.
Comprehensiveness of handling any and all situations that may arise is what we are looking for
(ie. handling no-match scenarios).
Some example utterances to illustrate the problem space are:
I want to buy a computer
What is the biggest hard disk I can buy
What have I bought in the last year
What is the cheapest price I can buy this for
Are there any sales or discounts available
Don&#39;t spend more than 30mins on this task.
