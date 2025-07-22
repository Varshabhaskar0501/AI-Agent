 # AI Agent to Answer E-commerce Data Questions
 An AI agent designed to answer e-commerce data questions by converting natural language queries into SQL, executing them against a MySQL database, and providing human-readable responses, with optional visualizations.
 ## Objective
The task is to build an AI agent that can:

●	Answer any question related to the data provided.

●	Receive questions via API endpoints, query the data, and respond with accurate answers.

●	Bonus: If possible, visualize the results and provide streamed responses (like live typing effect).

 ## Dataset
●	Product-Level Ad Sales and Metrics

●	Product-Level Total Sales and Metrics

●	Product-Level Eligibility Table

## Steps Followed
Steps to Follow
1.	Convert the datasets into SQL tables.

2.	Choose an LLM (Large Language Model) that can run locally (downloadable and usable without internet).

3.	Write a codebase that connects:

    ● The LLM,
  	
  	● The SQL tables,
  	
  	● And the API endpoints to receive and respond to questions.

5.	Implement logic so the AI agent can:

      ●	Understand the question,

      ●	Convert it into an SQL query,

      ●	Fetch the answer from the database,

      ●	And return it in a human-readable format.

5.	(Bonus) Add:

      ●	Graphs/visuals for certain queries,

      ●	Event streaming responses to simulate real-time interaction.

