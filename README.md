# candycrush-difficulty-analysis
Analysis of Candy Crush data used to estimate level difficulty. Data/some descriptions summarized from DataCamp.com.

Candy Crush has more than 3000 levels, and new ones are added every week. With these many levels, it's important to get level difficulty just right. Too easy and the game gets boring, too hard and players become frustrated and quit playing.

The dataset contains one week of data from a sample of players who played Candy Crush back in 2014. The data is also from a single episode (a set of 15 levels). 

Variables:

player_id: a unique player id
dt: the date
level: the level number within the episode, from 1 to 15.
num_attempts: number of level attempts for the player on that level and date.
num_success: number of level attempts that resulted in a success/win for the player on that level and date.

Analysis uses a Bernoulli process to find the probability of winning each of the 15 levels as well as the likelihood of winning all 15 levels in a single attempt.
