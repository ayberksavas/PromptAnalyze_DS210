# PromptAnalyze_DS210
## Description
Sabanci University DSA210 Introduction to Data Science Course Fall 2024-2025 Term Project.

**A project for analyzing my prompt history from two AI agents.**

## Table of Contents

  [Motivation](#motivation)
 
  [Data Source and Preprocessing](#data-source-and-preprocessing)
 
  [Project Idea and Plan](#project-idea-and-plan)
- [Data Visualization Plans](#data-visualization-plans)
 





## Motivation

While trying to find a dataset for the project, I initially considered basic data such as the calories I consume daily or the steps I take daily. However, I wasn't satisfied with this because the data only went back a few weeks. Then, I had this brilliant idea: **to analyze my prompt history with AI agents**. Since ChatGPT was released, I’ve been using it extensively, and I started using Claude a few months ago. This meant I had the perfect dataset—almost two years' worth of data that continues to grow daily as I study and ask questions. Moreover, this dataset is very informative about me, so analyzing it will be a journey of self-discovery. (Nosce te ipsum).

## Data Source and Preprocessing

I am using my chat history from ChatGPT and Claude AI agents as the primary dataset for this project. I downloaded the data from both platforms in JSON format. Since I used two separate ChatGPT accounts and one Claude account, I had three JSON files in total. To make the data easier to analyze, I combined all the files into a single CSV file. However, this process required overcoming certain challenges due to structural and format differences between the datasets.

## Project Idea and Plan

My idea is that I can uncover various interesting insights from this data. These insights are not only about me but can also reveal specific deadlines or events that took place. Additionally, I aim to explore the journey of getting to know myself better. I plan to analyze how AI perceives me and how it might profile me based on the questions I’ve asked.

I also want to investigate how my wording has changed over time when interacting with AI. For example, do I use bad language with AI? If so, why and when? 

Another idea I have is to analyze how my AI usage has changed over time, from when I first started using it to the present.

Furthermore, I plan to categorize my prompts into various topics, such as coding, personal development, entertainment, and academic inquiries. By analyzing these categories, I aim to identify patterns and trends in my interests and priorities over time. For instance, I want to see which topics I focus on most and how that focus shifts across different periods. This categorization will also help me better understand the relationship between my activities and significant life events.

#### Data Visualization Plans

I plan to use various visualizations to effectively communicate the insights derived from my analysis and make the data more engaging and accessible. **Pie charts** will illustrate the distribution of my prompts across different categories, such as coding, entertainment, personal development, and academic inquiries, providing a clear overview of where my focus lies. **Heatmaps** will visualize how my daily usage hours are distributed, revealing patterns in my interaction times and highlighting peak activity periods. To track changes in my AI usage over time, I will use **line charts** to represent trends and fluctuations, offering a temporal perspective on my engagement with AI. Additionally, **word clouds** will display some of the most frequently used words in my prompts, capturing common themes and key areas of interest in a visually engaging manner. These visual tools will help highlight trends in my interactions with AI over time, such as spikes in activity, shifts in focus across topics, and changes in language usage, uncovering insights at a glance.

These are the main aspects I’d like to work on, but I anticipate that new ideas might emerge during the analysis, leading me to add or remove topics as needed.

## Preview

Here’s an interesting finding I discovered during a rough analysis of the data:

![resim](https://github.com/user-attachments/assets/875a7d49-ca4c-4fb1-8fe0-da3404a0540e)

There are some specific outliers, as you can see. One of them is April 24th, a Wednesday, when I interacted with AI agents over 300 times. Upon investigation, I realized this spike occurred because we had a CS201 homework deadline that night at 10 PM. It’s so sad that I wasted time chatting with AI agents instead of working on my homework.

Another instance is March 17th and 18th, when I interacted with AI over 250 times across two consecutive days. When I looked into what happened on those days, I found out that my girlfriend had a Python homework deadline on March 18th. Again, it’s such a pity that I spent my time chatting with AI all day instead of helping my girlfriend with her homework.
