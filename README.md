# Studio-Ghibli-Data-Analysis
Studio Ghibli Films &amp; Characters Analysis

This project explores the world of Studio Ghibli by analyzing two JSON datasets: one containing all Ghibli films and another listing the characters who appear in those films. The goal of the project is to understand film trends, compare directors, and see whether cast size has any connection to film length or critical reception.

The project uses two semi-structured data sources from the Studio Ghibli REST API:


1) Ghibli Films API (film details, release years, ratings, running times)
2) Ghibli People API (character information and the films they appear in)


After loading, cleaning, and structuring both datasets, the project focuses on three main research questions:
1. How do Studio Ghibli films vary by release year, running time, and Rotten Tomatoes score?
We created a clean film summary and visualized trends across decades to see how film length and critical ratings have changed over time. This helps highlight the consistency and evolution of Ghibli’s storytelling style.

2. How do different directors compare based on their films’ average running time, average RT score, and total number of films?
We grouped films by director to understand their unique patterns. By looking at aggregated metrics—like average RT score and average film length—we’re able to see how each director contributes to the studio’s overall catalog.

3. Does a film’s cast size relate to its running time or Rotten Tomatoes score?
Using the joined film–character dataset, we calculated cast size for each film and compared it with running time and RT score. This helped explore whether movies with more characters tend to be longer or more highly rated.


Key Techniques Used

1. Loading semi-structured JSON from REST APIs
2. Saving raw datasets for reproducibility
3. Data cleaning and preprocessing
4. Normalizing nested fields with json_normalize()
5. Exploding list-based fields
6. Dataset joining based on shared URLs
7. Grouped analysis using pandas
8. Visualizations (scatter plots, bar charts, line graphs)
9. Generating summary CSV outputs


Tech Stack- Python, Pandas, Matplotlib, Requests, Jupyter Notebook, JSON

