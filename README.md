# keyword-network-analysis-and-word-frequency-analysis
 This repository contains Python code for keyword network analysis and word frequency analysis. It includes scripts to extract keyword data from a spreadsheet and convert it to a weighted adjacency matrix, compute node degree and strength, and generate top node lists and node pair weights. Additionally, it provides code for analyzing Twitter data of Elon Musk from 2017-2022, including word frequency computation, top word lists, histogram plots, and bigram network graphs.



The objective of project is to perform keyword network analysis and word frequency analysis
## Task 1
1. Download the dataset
(https://docs.google.com/spreadsheets/d/1GTwv07i98vL7S-J9eeP8NV1fJVnym
m1eJ31RDyt4Mxw/edit?usp=sharing)
2. Write a Python code to extract keyword data from the above file and convert it to a weighted adjacency matrix. See the figure below to understand the process
<img width="510" alt="Screen Shot 2023-05-10 at 12 34 55 PM" src="https://github.com/niral-desai/keyword-network-analysis-and-word-frequency-analysis/assets/46837140/bd03d89b-a3d4-4b60-b14a-958d064ad207">

3. Read the adjacency matrix and convert it into a weighted network
4. Compute node degree and strength
5. Show the top 10 nodes by degree and top 10 nodes by strength
6. Show the top 10 node pairs by weight
7. Plot average strength on y-axis and degree on x-axis

## Task 2
The link provides the twitter data of Elon Musk from 2010-2022. For analysis consider the years 2017-2022. Each year has thousands of tweets. Assume each year to be a document (all the tweets in one year will be considered as a document).
1. Compute word frequencies for each year. Exclude the stop words
2. Show top 10 words (for each year) by the highest value of word frequency
3. Plot histogram of word frequencies for each year
4. Use Zipf’s law and plot log-log plots of word frequencies and rank for each year
5. Create bigram network graphs for each year


