Retrieval-Augmented Generation (RAG) Model Evaluation

Project Overview

This project implements and evaluates a Retrieval-Augmented Generation (RAG) model using OpenAI’s API. It focuses on extracting information from web sources (such as Newegg) and leveraging LLMs to generate content-aware responses. The project was developed with reference to Don Woodlock’s YouTube tutorial: How to set up RAG - Retrieval Augmented Generation (demo). This was done with reference and help of youtuber Don Woodlock's video [How to set up RAG - Retrieval Augmented Generation (demo)](https://www.youtube.com/watch?v=P8tOjiYEFqU&list=LL&index=6&t=9s).

Key Features
	•	Automated Web Data Extraction: Retrieves structured data from specific web pages (e.g., Newegg) for knowledge augmentation.
	•	RAG Pipeline Implementation: Enhances OpenAI’s GPT-4o-mini model with external knowledge sources to improve response relevance.
	•	Multiple Prompt Strategies: Tests different input strategies, including direct questions and system prompts, to analyze model behavior.
	•	Similarity Metrics for Evaluation: Uses cosine and Euclidean distances to assess response consistency and accuracy.

Technologies Used
	•	Languages & Frameworks: Python
	•	Libraries: OpenAI API, Pandas, NumPy, SciPy, Swifter
	•	Tools: Web Scraping, Data Preprocessing, Retrieval-Augmented Generation

Setup Instructions
	1.	Clone this repository:

git clone <your-repo-link>
cd <your-repo-folder>


	2.	Install dependencies:

pip install openai pandas numpy scipy swifter  


	3.	Set up OpenAI API credentials by adding your API key to creds.py:

local_chatgpt_api_key = "your-api-key-here"


	4.	Run the Jupyter Notebook to explore data extraction, RAG implementation, and response evaluation.

Future Improvements
	•	Expand web page extraction to multiple sources for a broader knowledge base.
	•	Optimize prompt engineering for better factual consistency.
	•	Integrate more advanced evaluation metrics beyond cosine and Euclidean distances.
