# real-time-crypto-ranking
a real-time search system that handles cryptocurrency data with the CoinCap API

In this code:

**Fetching Real-time Cryptocurrency Data:**
We use the CoinCap API to fetch the latest cryptocurrency data periodically.

**Preprocessing and Embeddings:**
Each description is preprocessed to remove noise and standardize the text.

We employ the Sentence Transformers model to generate semantic embeddings for the preprocessed descriptions.

**Building a FAISS Index:**
We create a FAISS index to efficiently store and retrieve embeddings for similarity search.

The embeddings of the cryptocurrency descriptions are added to the FAISS index.

**Search Functionality:**
A search function is defined to query the FAISS index based on user input.

It returns the top results along with their distances.

**Example Query:**
An example query ("blockchain") is provided to demonstrate real-time search functionality.
This code is used for real-time analysis of cryptocurrency descriptions, enabling users to quickly find relevant cryptocurrencies based on their queries. For instance, users can search for "blockchain" to find cryptocurrencies related to blockchain technology.
