**RestoRecommender: AI-Powered Restaurant Recommendation System**

RestoRecommender leverages the power of artificial intelligence (AI) to suggest restaurants and bars based on user preferences and review analysis. It utilizes Retrieval-Augmented Generation (RAG) to extract meaningful insights from customer reviews.

**Functionality Breakdown:**

* **Data Collection (`places.ipynb`):**
  - This Jupyter Notebook scrapes data from Google Maps's Places API and stores the extracted information in CSV files (`places.csv` and `reviews.csv`) within the `data` directory.

* **RAG LLM Model Creation (`rag_chatbit.ipynb`):**
  - This script outlines the process of building a RAG-based large language model (LLM). The steps involve:
      - Data loading from CSV files
      - Vector database construction
      - Embedding model training
      - LLM model creation
  - The notebook also showcases demonstration use cases and evaluations based on synthetically generated questions.

* **Answer Generation (`experiments.ipynb`):**
  - This Jupyter Notebook utilizes the `questions.txt` file containing user queries to generate corresponding answers and saves them in the `Question-Answer.txt` file. It allows for the inclusion of additional user questions for enhanced personalization.

