# GeoClassification of Subreddit Posts (Canberra, Boston, Geneva, Ottawa)

This Jupyter Notebook (geoclassification_subreddit_posts.ipynb) demonstrates how to classify the text of subreddit posts into four cities: Canberra, Boston, Geneva, and Ottawa. It covers data cleaning, exploratory analysis, model training, and evaluation steps, all within a single notebook.

--- 
## Overview

In this project, we aim to predict the city to which a subreddit post is most likely related based on textual cues. The four target cities are:
	•	Canberra (Australia)
	•	Boston (USA)
	•	Geneva (Switzerland)
	•	Ottawa (Canada)

Key goals include:
	•	Data Preprocessing: Cleaning raw subreddit text (removing punctuation, emojis, special characters).
	•	Feature Engineering: Using methods like TF-IDF or word embeddings to represent text.
	•	Classification: Training supervised machine-learning models (e.g., Logistic Regression, Naive Bayes, or a neural network) to categorize posts by city.

---

## Data Source & Structure
	•	Data: Subreddit posts pulled from relevant subreddit communities (or any text dataset referencing the above cities).
	•	Structure: Each text sample is paired with a label (the city).
	•	Format: A CSV or DataFrame is typically loaded, containing columns like post_text and city_label.


 ## Performance
 
 <img width="506" alt="Screenshot 2025-04-08 at 3 48 38 PM" src="https://github.com/user-attachments/assets/1acdc37d-f23b-44a7-9a2c-05a2e41efdf5" />
