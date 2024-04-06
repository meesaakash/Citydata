# Citydata
Data analysis on New York City maps aims to identify promising store locations for selling a new Ready-to-Drink (RTD) protein shake product. Using the Google Maps Places API, I identified grocery stores and markets near subway stations with high foot traffic, targeting middle to higher income buyers. To understand buying trends related to the description of my RTD protein shake audience, I followed these steps:

- Extracted store reviews using the Google Maps API, focusing on locations near subway stations (where people would conveniently grab the protein shake during their commute to work).
- Summarized the reviews using an LLM summarization model via HuggingFace APIs to establish a general overview.
- Analyzed correlations between the general summary and my product’s target audience using another comparison model via HuggingFace, rating the correlation on a scale from 0 to 1.
- Flagged stores with high ratings for further consideration.

Next steps involve improving accuracy and exploring additional businesses that could potentially sell RTD protein shakes (maybe cafes or gyms).
