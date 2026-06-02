# 🟢 Easy Questions

Here is where all of the Easy questions are stored.

Feel free to have a look through!

# 📖 Contents
1. [Twitter SQL: Histogram of Tweets](https://github.com/riley-millard/DataLemur-SQL-Questions/blob/main/Easy/README.md#1-twitter-sql-histogram-of-tweets)

# ❓ Questions

Questions and solutions are below.

# 1. Twitter SQL: Histogram of Tweets

## Scenario

Assume you're given a table Twitter tweet data, write a query to obtain a histogram of tweets posted per user in 2022. Output the tweet count per user as the bucket and the number of Twitter users who fall into that bucket.

In other words, group the users by the number of tweets they posted in 2022 and count the number of users in each group.

## Data

<img width="907" height="743" alt="image" src="https://github.com/user-attachments/assets/bbaaf906-a07b-4690-b62b-305d3e9f4333" />

<img width="889" height="394" alt="image" src="https://github.com/user-attachments/assets/b52d0966-fb8d-48d5-8f2c-44d57f1810cc" />

## My Solution

First, I needed to find how many tweets were posted by each user in 2022:

<img width="901" height="643" alt="image" src="https://github.com/user-attachments/assets/5a331c49-7c6b-4834-8127-7e16f9e301d4" />

Based on this data, I can see that in 2022, user 111 posted 2 tweets, but 148 and 254 only posted one each.

Now to get the final result for this question, I use the tweet_count_per_person as the bucket for counting the number of users by tweet volume.

This gives us the final output below:

<img width="933" height="654" alt="image" src="https://github.com/user-attachments/assets/ad425019-6f6f-4cab-a7ce-b2021f29862b" />


