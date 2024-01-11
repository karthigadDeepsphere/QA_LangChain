Questions Answering in Langchain:
In Questions Answering using Langchain/LLM, there are 4 different ways for question-answering. They are:

 load_qa_chain: It is a generic interface for question-answering. It takes the input of all the text in the document.
	RetrievalQA: Here we retrieve most relevant text chunks and feed it to language model
	VectorstoreIndexCreator: It is a higher level interface that is wrapped around RetrievalQA functionality.
	ConversationalRetrievalChain: It is similar to RetrievalQA, but in addition it provides a chat history parameter which can be used for follow up questions.

Questions to ask:

1.	What are the key advantages of establishing reciprocity early when changing retirement systems under CalPERS?
2.	How does the Public Employees’ Pension Reform Act of 2013 (PEPRA) impact new members joining CalPERS?
3.	What are the requirements for achieving full reciprocity in the CalPERS retirement system?
4.	How does the Final Compensation Exchange work for CalPERS members who move between reciprocal retirement systems?
5.	Can you explain the process and significance of redepositing withdrawn CalPERS contributions when joining a qualifying reciprocal system?

Follow-up questions for conversational retrieval chain method:

1.	From the above which is important advantages?
2.	Who need to complete self-certification?
3.	How many years of credit services?
4.	What is the highest compensation?
5.	Will services credit increase?
