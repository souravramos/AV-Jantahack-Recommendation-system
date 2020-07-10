# Programming-Challenges-Recommender-System-using-LSTM

## Overview
This is a simple recommender system which predicts next 3 challenges the user might be interested to solve given the history of last 10 challenges the user has solved.

## Dataset Description

We have three data files:


        train.zip:it contains two files:
            train.csv: It contains the set of 13 challenges that were attempte­­d by the same user in a sequence
            Variable 	Definition
            user_sequence 	Unique ID for the sequence
            user_id 	User ID
            challenge_sequence 	Challenge sequence number (1-13)
            challenge 	Challenge ID
             
            challenge_data.csv: Contains attributes related to each challenge
            Variable 	Definition
            challenge_ID 	Challenge ID
            programming_language 	Programming language for the challenge
            challenge_series_ID 	Series for the given challenge
            total_submissions 	Total submissions by all users
            publish_date 	Publishing date for the challenge
            author_ID 	Author ID
            author_gender 	Author gender
            author_org_ID 	Organization ID for author
            category_id 	Type of challenge
