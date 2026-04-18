
# CSL7110 Assignment 4  
### Clustering • Web Search • PageRank  

**Name:** Kunal Mishra  
**Roll Number:** M25CSA036  
**Course:** Machine Learning with Big Data (CSL7110)  

---

## Overview

This assignment focuses on implementing three important concepts used in real-world data systems:

- Clustering using k-center and k-means++  
- Web search using inverted index and TF-IDF  
- PageRank algorithm for ranking nodes in a graph  

The objective was to understand both the implementation and practical behavior of these algorithms on real datasets.

---

##  Dataset Information (Important)

The datasets are **not included in this repository**.  
To run the project successfully, you must manually download and place them in the correct folders.

---

### 🔹 Part 1: Clustering Dataset

- Dataset: UCI Spam Dataset  
- Download from:  
  https://archive.ics.uci.edu/ml/datasets/spambase  

After downloading:
- Place the dataset file inside the `Q1/` folder  
- Ensure each row contains comma-separated numerical values  

---

### 🔹 Part 2: Web Search Dataset

This dataset is provided as part of the assignment files.

Folder structure should be:

```
Q2/
├── webpages/
├── actions.txt
└── answers.txt
```


Make sure all files are placed exactly in this structure.

---

### 🔹 Part 3: PageRank Dataset

Required files:
small.txt
whole.txt


Each line in these files represents an edge:

Place both files in the root directory of the project.

---

## Repository Structure

```
.
├── Q1_Clustering.ipynb
├── Q2_WebSearch.ipynb
├── Q3_PageRank.ipynb
└── M25CSA036_CSL7110_Assignment4.pdf
```

---

## How to Run

You can run this project using **Jupyter Notebook or Google Colab**.

---

### ▶️ Part 1: Clustering

Open:Q1_Clustering.ipynb


Run all cells to get:
- k-center execution time  
- k-means++ objective  
- Hybrid objective  

---

### ▶️ Part 2: Web Search

Open:Q2_WebSearch.ipynb

This reads input from `actions.txt` and outputs:
- Pages containing a word  
- Word positions  
- Ranked results using TF-IDF  

---

### ▶️ Part 3: PageRank

First run on small dataset:
```python
file_path = "small.txt"

Then run on full dataset
file_path = "whole.txt"

**Outputs:**

- Top 5 nodes  
- Bottom 5 nodes  
- Convergence graph  

Key Results

Top Ranked Nodes (PageRank):
263  0.00202029
537  0.00194334
965  0.00192544
243  0.00185263
285  0.00182737

Lowest Ranked Nodes:
408  0.00038779
424  0.00035481
62   0.00035314
93   0.00035135
558  0.00032860

Visualization
PageRank convergence over iterations:

## Assumptions

- Stop words are ignored in the search  
- All text is converted to lowercase  
- Duplicate edges are treated as one  
- Each node distributes rank equally among outgoing links  
- Euclidean distance is used for clustering

## Final Thoughts

This assignment demonstrates how clustering, search indexing, and graph ranking are applied in real-world systems. It helped in building both conceptual understanding and practical implementation skills.

## GitHub Repository

Github Repo Link: (https://github.com/Givhel/MLBD_Assignment4_Clustering-and-PageRank/edit/main/README.md)






