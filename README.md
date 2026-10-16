# Leaderboard for Bubble Bobble Raylib
This is the repository for the leaderboard page for [BubbleBobbleRaylib](https://github.com/Gitionia/BubbleBobbleRaylib). The page is available at https://gitionia.github.io/bubble-bobble-raylib-online/leaderboard/

# Functionality
- The leaderboard shows the round, score, player name and date
- You can search the leaderboard by any of the columns and also display only a range of rows (e.g. 4-10)

# Notes
- The leaderboard is stored on a supabase database 
- The database contains only the following data: 
    - A timestamp when it was added
    - A player name of length 3, set by the player
    - The score
    - The level that was reached
    - The version of the game, on which the score was reached (not displayed on the page)
- The data is only sent by the game if the player confirms that they want to add their score to the leaderboard

- The font used is from: https://style64.org/release/c64-truetype-v1.2.1-style

- If you have questions about the data or want to remove an entry from the leaderboard, you can send an email to 2pz92bns7@mozmail.com
