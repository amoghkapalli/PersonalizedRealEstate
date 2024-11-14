Project Description:
This project aims to create a personalized real estate agent by leveraging large language models and vector databases to transform standard real estate listings into personalized narratives that resonate with potential buyers' unique preferences and needs.

I utilized the following steps to accomplish this task:
1. Generate Real Estate listings by providing a prompt to GPT-3.5 asking for a list of 10 real estate listings. I provide an example so that the format could be understood by the llm.
2. I stored these listing in a vector database and created embeddings for the combined description of both the neighborhood and the house. This provides an embedding for text of a larger scale covering not only customers wants/needs for the house but also the neighborhood.
3. I build a user preference interface with asking for user input for 4 questions I found could be helpful. In the Jupyter notebook you can see a example of some text I inputted as a sample users response
4. I performed a semantic search on the vector database by taking the buyers preferences and getting the top 3 most similar results when compared with the combined description.
5. After a lot of fine tuning, I found a prompt that gave me a good response as a realtor talking about each of these three homes. It provides a good pitch on the homes along with a good introduction.


HOW TO RUN:

You can run this program by providing your own OPENAI API Key on cell 6 and then running all the cells. Note: You may need to restart the notebook after importing the necessary packages.