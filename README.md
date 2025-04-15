# Data Science Portfolio

## Project 1: [Truth and Deception: Can Data Reveal When Someone is Lying?](https://github.com/Gitbyt3/Predicting-Truths-and-Lies)
**Objective:** Use a dataset of audio stories to develop a model capable of classifying the stories as truthful or deceptive
- 100 unique, 2 minute audio stories were used, each labelled as truthful or deceptive
- Librosa was used to extract audio features across the time and frequency domains, and artificially extend the dataset through audio augmentation
- Ensemble models were developed to aggregate model performance across three machine learning models, resulting in an ultimate performance of 88% accuracy

![Screenshot 2024-12-29 173641](https://github.com/user-attachments/assets/be34674f-45da-4df9-b087-0e8a048a40cf)

## Project 2: [Video Game Search Engine](https://github.com/Gitbyt3/SUPREME-Video-Game-Search-Engine)
**Objective:** Design and implement a search engine capable of retrieving video game titles from a video game dataset
- Multiple modules were designed and implemented on Python including query processing, candidate retrieval, and retrieval ranking
- These modules were combined as a retrieval pipeline and accessed using a web interface
- Games were ranked according to semantic similarity and keyword matching

![Screenshot 2025-04-15 202744](https://github.com/user-attachments/assets/04082414-5681-42e5-9028-3518907197e3)

## Project 3: [Convolutional Neural Network (CNN) to Classify CIFAR-10](https://github.com/Gitbyt3/CIFAR-10-CNN)
**Objective:** Classify images from 10 different classes using a CNN built and trained on Pytorch
- The network was fully designed and trained on Pytorch
- The final test accuracy was 92.3%
- Many hyperparameters were tested and implemented including design changes, regularisation techniques, and training optimisations

![Screenshot 2025-04-03 115700](https://github.com/user-attachments/assets/f2059cb0-1e85-4b57-af42-aa50da214035)

## Project 4: [Scrappy - A Job Post Scraper](https://github.com/Gitbyt3/Job-Scraper-Scrappy)
**Objective:** Centralise and automate newly posted jobs in a single Google Sheet using webscraping
- Job boards used were LinkedIn, Glassdoor, and Indeed
- This scraper used Python's Selenium and BeautifulSoup libraries to automatically crawl job posting every single day and automatically upload them to my Google Sheets
- The queries are customisable depending on location, experience level, and job title
- With this scraper, I can spend more time on the job postings that matter to me and less time looking for them

## Project 5: [Publication Click-Rate Analysis for a Think Tank](https://github.com/Gitbyt3/Click-Rate-Analysis)
**Objective:** Investigate trends in publication downloads & views and identify their causes
- Data was sourced from two internal databases, one containing click data and the other containing publication characteristics
- Extensive data wrangling was conducted as the raw click data was near unusable in its original state
- The regression analysis uncovered multiple variables potentially responsible for the downloads/views. These were:\
  &nbsp;&nbsp;&nbsp;&nbsp; 1. Frequency of publication releases\
  &nbsp;&nbsp;&nbsp;&nbsp; 2. Publication type\
  &nbsp;&nbsp;&nbsp;&nbsp; 3. Publication topic
- Below is an example of an exploratory visualisation from the project generated using the Seaborn data visualisation library
<p align="center">
  <img width="400" alt="Screenshot 2023-11-11 170247" src="https://github.com/Gitbyt3/Portfolio/assets/142446962/b5a9a662-97d0-4e96-9798-ebf980afe4a7">
</p>
