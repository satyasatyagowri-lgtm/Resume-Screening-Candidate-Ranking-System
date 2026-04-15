# Resume Screening & Candidate Ranking System

## Project Overview

This project is a Machine Learning based system that automatically screens resumes and ranks candidates based on their relevance to a job description. It helps reduce manual effort in recruitment and improves candidate selection efficiency.

## Features

Resume text preprocessing using NLP techniques. Job description matching. Similarity scoring using TF-IDF and Cosine Similarity. Candidate ranking based on role fit. Identification of missing skills.

## Technologies Used

Python, Natural Language Processing (NLP), NLTK, Scikit-learn, TF-IDF Vectorization.

## Methodology

Resume text is cleaned using preprocessing techniques such as lowercasing and stopword removal. Both resumes and job descriptions are converted into numerical vectors using TF-IDF. Cosine similarity is used to calculate how closely each resume matches the job description. Candidates are ranked based on similarity scores.

## Example Output

Score: 0.26
Missing Skills: {communication}

## Conclusion

This project demonstrates how Machine Learning and NLP can be applied in recruitment systems to automate resume screening and improve hiring decisions.
