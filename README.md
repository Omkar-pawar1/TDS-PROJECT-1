1.For scraping I first read about github api's documentation to get to know api structure and used python module called 'PyGithub'.It has direct methods which made my 
task very easy.This is link of colabnotebook in which I did my scraping 'https://colab.research.google.com/drive/1eK--UMX4D1K7NsvK1t97DBJLVbDXsONx'.
2.
Data insights from users.csv
    Average Metrics:
    Average Followers: 835.9973821989529
    Average Public Repositories: 100.86387434554973

3.Insights from repositories.csv

  
  1. Most Popular Languages
      The top 10 most frequently mentioned programming languages include a variety of tools, but many repositories lack specified languages.
  
  2. Top Starred Repositories
      The most starred repositories include:
      huggingface/transformers with 134,100 stars.
      Genymobile/scrcpy with 111,061 stars.
      strapi/strapi with 63,519 stars.
      Other notable repositories focus on animation, system management, and visual tools.
  
  3. Licensing Trends
      Popular licenses include MIT, Apache 2.0, and GPL, but a large number of repositories have no specified license.
  
  4. Temporal Trends
      There is a noticeable increase in repository creation over the years, reflecting the growing adoption of open-source practices.
  
  5. Feature Adoption
      About 50% of repositories support project boards (has_projects).
      Approximately 50% have wikis enabled (has_wiki).
     
  7. User Activity
      The most prolific contributors (users with the most repositories):
      revolunet with 500 repositories.
      MysteriousSonOfGod with 500 repositories.
      Haroenv and others close behind.
     
** SOME DEEPER ANALYSIS **

1. Star Distribution Analysis
      Most repositories have few or no stars, with 50% having 0 stars.
      However, a small number of repositories have exceptionally high stars, creating a long-tail effect:
      The top repository has 134,100 stars.
      Only 25% of repositories have more than 2 stars, highlighting a concentration of popularity in a few repositories.

2. Temporal Trends with Star Growth
    Repository stars grow consistently over the years, but more recent years (2018–2023) show a sharp increase in total stars.
    This may indicate increasing adoption of repositories and interest in newer technologies.

3. Popular Languages by Stars
    The top 10 languages by total stars:
    JavaScript leads with the highest total stars.
    Other prominent languages include Python, HTML, and TypeScript.
    Java and PHP maintain a significant but slightly lower presence.

4. Missing License Analysis
    Over 16,448 repositories (44% of the dataset) lack a specified license.
    These repositories have a significantly lower average star count (12.16 stars) compared to the dataset average (52.39 stars).
    The most common languages in repositories without licenses:
    JavaScript, HTML, and Python dominate.

5. Active Users' Contributions
    Top contributors based on total stars across their repositories:
    huggingface leads with 411,267 stars.
    Other notable users include Genymobile and strapi developers.
    These users seem to focus on repositories that gather significant attention and interest.

  
