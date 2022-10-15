# Guess the Score


This project will try to replicate the old "guess the score" functionality. Nobody has started anything yet, I'm just laying out the requirements:

1. Python
2. PRAW
3. NHL API - information available here: https://github.com/dword4/nhlapi

Pseudo workflow:

1. Bot must access the subreddit and look for a game thread.
2. If one exists, make a comment with the guess the score instructions (take them from /u/orlandkurtenbot's old posts)
3. Sticky the comment
4. When the game starts, cut off submissions.
5. Document all submissions
6. Check for a post-game thread
7. Make a post and sticky it with any/all winners & leaderboards
8. Record points to database for leaderboards
