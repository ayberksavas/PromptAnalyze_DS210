# PromptAnalyze_DS210
## Description
Sabanci University DSA210 Introduction to Data Science Course Fall 2024-2025 Term Project.

Here is my presentation video: https://drive.google.com/drive/folders/1ZMlPi14MowiAuxD7I3tGQ_dQSvvXjYND?usp=drive_link 

A project for **analyzing my prompt history from two AI agents.**

## Table of Contents

  [Motivation](#motivation)

  [Tools](#tools)
 
  [Data Source and Preprocessing](#data-source-and-preprocessing)
 
  [Project Idea and Plan](#project-idea-and-plan)
- [Data Visualization Plans](#data-visualization-plans)

[Preview](#preview)
 





## Motivation

While trying to find a dataset for the project, I initially considered basic data such as the calories I consume daily or the steps I take daily. However, I wasn't satisfied with this because the data only went back a few weeks. Then, I had this brilliant idea: **to analyze my prompt history with AI agents**. Since ChatGPT was released, I’ve been using it extensively, and I started using Claude a few months ago. This meant I had the perfect dataset—almost two years' worth of data that continues to grow daily as I study and ask questions. Moreover, this dataset is very informative about me, so analyzing it will be a journey of self-discovery. (Nosce te ipsum).

## Tools

**ChatGPT and Claude:** Used to assist with almost all questions I have. They form the foundation of my project since I obtain my data from them.

**Visual Studio Code:** For coding and implementing libraries.

**Pandas:** Used for data cleaning and structuring.

**Matplotlib:** For creating visualizations.

**NumPy:** For performing mathematical operations.

**Seaborn**: For data visualization(heatmaps)

**Wordcloud**: For creating word clouds about chat history

These are the tools I have used so far. I will update this list as needed.

## Data Source and Preprocessing

I am using my chat history from ChatGPT and Claude AI agents as the primary dataset for this project. I downloaded the data from both platforms in JSON format. Since I used two separate ChatGPT accounts and one Claude account, I had three JSON files in total. To make the data easier to analyze, I combined all the files into a single CSV file. However, this process required overcoming certain challenges due to structural and format differences between the datasets.

## Project Idea and Plan

My idea is that I can uncover various interesting insights from this data. These insights are not only about me but can also reveal specific deadlines or events that took place. Additionally, I aim to explore the journey of getting to know myself better. I plan to analyze how AI perceives me and how it might profile me based on the questions I’ve asked.

I also want to investigate how my wording has changed over time when interacting with AI. For example, do I use bad language with AI? If so, why and when? 

Another idea I have is to analyze how my AI usage has changed over time, from when I first started using it to the present.

Furthermore, I plan to categorize my prompts into various topics, such as coding, personal development, entertainment, and academic inquiries. By analyzing these categories, I aim to identify patterns and trends in my interests and priorities over time. For instance, I want to see which topics I focus on most and how that focus shifts across different periods. This categorization will also help me better understand the relationship between my activities and significant life events.

### Data Visualization Plans

To effectively communicate my findings, I plan to use the following visualizations:

  **Pie Charts**: To show the distribution of prompts across categories like coding, personal development, entertainment, and academic inquiries.
  
  **Heatmaps**: To display daily usage patterns, revealing peak activity times.
   
  **Line Charts**: To track trends in AI usage over time, highlighting fluctuations and patterns.
    
  **Word Clouds**: To visualize the most frequently used words in my prompts, capturing key themes at a glance.

These visual tools will help highlight trends such as spikes in activity, shifts in focus, and changes in language usage over time.

These are the main aspects I’d like to work on, but I anticipate that new ideas might emerge during the analysis, leading me to add or remove topics as needed.

## Preview

Here’s an interesting finding I discovered during a rough analysis of the data:

![resim](https://github.com/user-attachments/assets/875a7d49-ca4c-4fb1-8fe0-da3404a0540e)

**-March 17th and 18th:** Over 250 interactions with AI agents across two consecutive days. Upon investigation, I found that **my girlfriend had a Python homework deadline on March 18th**. It’s such a pity that I spent time chatting with AI instead of helping her with her homework(!).

**-April 24th:** Over 300 interactions with AI agents. This spike coincided with the **CS201 homework deadline** that night at 10 PM. Unfortunately, I wasted time chatting with AI instead of focusing on my own assignment(!).
