# Simple Market Chatbot

This is a simple command-line chatbot that helps users (buyers or sellers) find matching product listings in a simulated marketplace. It leverages Natural Language Processing (NLP) with SpaCy for Named Entity Recognition (NER) to extract key information from user requests.

## Features

- **Role Selection:** Users can specify if they are a 'buyer' or a 'seller'.
- **Named Entity Recognition (NER):** Extracts 'product', 'quantity', and 'price' from user input using SpaCy and custom rules.
- **Product Matching:** Searches a dummy database for listings that match the user's request.
- **Scoring System:** Ranks matches based on criteria like quantity and price proximity, optimized for buyer (lower price) or seller (higher price) preferences.
- **Top 3 Results:** Displays the top 3 most relevant matches.

## Project Structure