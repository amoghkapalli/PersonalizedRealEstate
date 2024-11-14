# Personalized Real Estate

## Project Description
This project is a proof of concept to create a personalized experience for each buyer, making the property search process more engaging and tailored to individual preferences.

I performed the following steps for this project:

1. Generated structured real estate listings using a large language model (LLM) to populate the database.
2. Converted the listings into embeddings and stored them in a vector database.
3. Built a user preference input with several questions for the user to answer.
4. Performed a semantic search on the vector database to retrieve listings that closely match the user's requirements.
5. Using the top results from the semantic search, utilized the LLM to generate detailed descriptions for each property.

## Future Extensions
To enhance the functionality and real-world applicability of this project, a next step could involve integrating real house listings from Zillow. By using Zillow's API, we could access up-to-date and localized property data, enabling the following improvements:

- **Real-Time Listings**: Pull real estate listings in real-time to keep the database fresh with accurate and current properties.
- **Enhanced Property Data**: Incorporate additional listing details such as neighborhood insights, historical pricing, and school ratings.
- **Market Analytics**: Provide users with personalized insights on market trends based on their preferences and recent searches, allowing them to make informed decisions.
