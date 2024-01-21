Web Scraping Project Readme
Objective
The objective of this project is to scrape data from a website, specifically from https://github.com/topics. The goal is to gather information about different topics on GitHub, including the topic title, topic page URL, topic description, and the top 25 repositories within each topic. For each repository, we aim to extract the repository name, username, stars, and repository URL.

Project Outline
Scraping Topics:

Target website: GitHub Topics
Information to scrape:
Topic title
Topic page URL
Topic description
Scraping Top Repositories within Each Topic:

For each topic, gather information about the top 25 repositories.
Information to scrape:
Repository name
Username
Stars
Repository URL
Output Format:

Create a CSV file for each topic with the following format:
mathematica
Copy code
Repo_name, Username, Stars, Repo URL
Project Strategy
Jupyter Notebook:

Utilize a Jupyter notebook to outline the project strategy.
Use the "New" button above to create a new Jupyter notebook.
Step 1 - Project Idea:

Browse through different sites to pick one for scraping.
Check the "Project Ideas" section for inspiration.
Identify the information to scrape and decide the format of the output CSV file.
Summarize the project idea and outline the strategy in the Jupyter notebook.
Step 2 - Download Web Pages:

Use the requests library to download web pages.
Inspect the website's HTML source to identify the relevant URLs.
Download and save web pages locally using the requests library.
Create a function to automate downloading for different topics/search queries.
