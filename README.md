# AISpring
This is AI Study Repo along with info and project 

#Token:
Simmilar to english word of 4-5 charachters to identify text used by AI , it is fundamental of AI 
https://platform.openai.com/tokenizer // Check yourself
<img width="928" height="729" alt="image" src="https://github.com/user-attachments/assets/f41b40a2-ed43-400c-a063-b11a537af1a9" />
<img width="807" height="617" alt="image" src="https://github.com/user-attachments/assets/c95e7180-2cbf-489a-9b28-2b11396515b2" />

Output generally cost more than input token. Companies generally charge cost per million tokens and We have to use AI in such a way that it will be in budget.

Normal Chat can take less token , RAG or doc process will take more.

#Vector Embedding
The Bank in English means 2 meaning 1. Financial 2. River side
So to check the correct meaning it will check Vector Embedding in that 1536 dimensions are there , Map co-ordinates have 2 so that's huge !! So We can find the elemnent is used in what context.

https://www.pinecone.io/learn/vector-embeddings/
Visualize : https://projector.tensorflow.org/


This chapter will show you how AI converts words into numbers that capture meaning, enabling powerful features like semantic search and RAG systems.
Important note: Vectors and embeddings are the same thing in AI. We'll use both terms interchangeably throughout this course.

The Problem: Tokens Have No Meaning

Let's start with the fundamental problem that embeddings solve.

When AI processes the word "King", it becomes Token ID 7948. The word "Monarch" becomes Token ID 32541.

Here's the issue: to the computer, these are just numbers. The IDs 7948 and 32541 have no mathematical relationship - they're as unrelated as 7948 and 1,000,000.

But we humans know that "King" and "Monarch" mean almost the same thing!

Problem 2: Context Blindness

The word "bank" gets the same token ID whether it means:

A financial institution ("I deposited money at the bank")
The side of a river ("We sat on the river bank")

Same token, completely different meanings. The AI is blind to context.

This is why we need vectors - to capture meaning, not just identity.
