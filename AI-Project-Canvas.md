# AI project Canvas

In this project, we will build a chatbot that acts as a fashion assistant for Amazon's fashion e-commerce department. 

## Problem Statement

In the last 20 years, e-commerce fashion players relied on 2 major entrypoints for driving sales growth:
- Recommendation systems for personalization: these systems facilitate product discovery and drive a seamless experience
- Search for identifying user explicit intent and retrieving relevant products for users

With the advent of LLMs, e-commerce players can now have Agentic RAGs a new entrypoint to drive growth. Such a chatbot can
play the role of a shopping assistant and it can adapt to users' changing preferences in quasi real-time. 

**How it works**: a user enters a query into the chatbot asking it to recommend relevant fashion items for a specific event in a specific location. The 
chatbot would then retrieve relevant products and display them to the user. The user can then browse these products and purchase them or they can prompt the 
chatbot to refine the recommendations.

Such a chatbot is expected to drive an increase in 5%-10% in user monthly GMV.

In contrast to traditional recommender and search systems, a fashion Agentic chatbot can be steered by a user allowing a more nuanced
executionn of personalized recommendation.

## Data & Knowledge

### Data sources:
We assume that the data sources below are of acceptable quality (tabular data with an tolerable % of missing/erroneous records). But this assumption needs to be assessed.
#### Unstructured/Semi-structured
- product catalogues with metadata descriptions (composition, color, ...)
- [Optional] Product images (from URL description)
#### Tabular Data 
- user historical data (last 1 year of data)
- product inventory data (to filter out unavailable products) (current)
### Preprocessing & Augmentation
- clean product descriptions
- for the MVP: only consider items that sold > 1000 units and with at least 100 reviews
### Retrieval
- embed product descriptions of individual skus in a vector database using pre-trained embedding models
- augment user query with relevant retrieved descriptions

## AI Approach & Methodology

- Use a standard LLM such as gpt-4o-mini or gemini-flash without fine-tuning
- 

## Performance Metrics & Evaluation Rules


## Resources & Stakeholders

## Risks & Mitigation

## Deployment & Integration

## AI Approach & Methodology

### Timelines & Milestones
