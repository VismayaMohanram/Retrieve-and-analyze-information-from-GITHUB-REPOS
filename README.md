Used Python and GitHub API to retrieve information of the past 2 months for the given repositories.

1. https://github.com/openai/openai-cookbook 
2. https://github.com/elastic/elasticsearch 
3. https://github.com/openai/openai-python
4. https://github.com/milvus-io/pymilvus/
5. https://github.com/SebastianM/angular-google-maps

Created vector embeddings for the issues retrieved and stored them in ElasticSearch (Push, Pull, and Readme directories)
1) Created a Bar Chart to plot the number of issues created for every repo for every day of the week; that is total number of issues created on Monday, Tuesday, Wednesday …, Sunday for EVERY Repo name.
2)Used vector embeddings, score, and semantic search to identify and list the Top 5 most similar issues for every repo listed above.
