# Social Media Performance and Engagement Analysis

## Overview

This project analyzes a social media performance dataset to discover possible associations between a post's content type, platform, and topic. The main goal is to understand whether certain content formats, such as videos, images, reels, carousels, or text posts, are more strongly associated with certain topics, such as food, travel, health, lifestyle, or entertainment. This type of analysis can be useful for content creators, social media platforms, and marketing teams because it can help identify which topics are commonly connected to different content formats and platforms.

**Start here:** [`main_notebook.ipynb`](./main_notebook.ipynb)

**Project video:** [`2-minute.mp4`](./2-minute.mp4)

---

## Research Questions

This project focuses on the following research questions:

1. **What is the association between a social media post's content type and topic?**  
   For example, if a post is a video, what topic is it most likely associated with?

2. **What is the association between a social media platform-content type pair and a post's topic?**  
   For example, if a post is an Instagram reel, what topic is it most likely associated with?

These questions are explored using association rule mining concepts such as **support**, **confidence**, **interest**, and **lift**.

---

## Data

The dataset used in this project is a social media performance and engagement dataset from Kaggle. It contains information about social media posts, including platform, post type, engagement metrics, and content-related features.

The dataset used in this repository is located here:

```text
data/social_media_performance.csv
```

[Link to website origin of dataset](https://www.kaggle.com/datasets/svthejaswini/social-media-performance-and-engagement-data?resource=download)

---

## Python Version

```text
Python 3.12.13
```
---

## How to Reproduce This Work

This project was developed in **Google Colab**. To reproduce the analysis, follow these steps:

1. Open the main notebook in Google Colab:

```text
main_notebook.ipynb
```

2. Make sure the dataset is located at:

```text
data/social_media_performance.csv
```

3. Run the notebook from top to bottom.

4. If running locally instead of Colab, install the required packages with:

```bash
pip install -r requirements.txt
```

---

## Key Dependencies and Versions

This project was built using Python in Google Colab. The full environment is listed in [requirements.txt](./requirements.txt).

The most important packages used in this project are:

- Python
- pandas
- NumPy
- matplotlib
- mlxtend
- Google Colab


The [requirements.txt](./requirements.txt) file contains the complete list of package versions needed to reproduce the notebook environment.

---
