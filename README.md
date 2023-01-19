# TV Picker
Find the code for different iterations of my TV picker function. The function takes in a name of a TV show and tells you a random episode of it to watch! As someone who rewatches the same TV shows and movies, sometimes I need a random episode to watch. So, I wrote this function to help me decide. 

***
METHODS (CHRONOLOGICAL)

1. Rmd file with chunks to separate writing the data libray, writing the function, and calling a function
2. .R script with the same content as version 1 (.Rmd)
3. R project file, which was a great improvement, but required a folder to be the project directory. I want to simplify use of this function, so it is a bit counter productive.
4. .RData file is the best solution I have found. It loads the environment, so I can glance at the TV shows available and call the function at the same time.


***
UPDATES

January 18 2023: As of now, all iterations do not weight each episode equally. Each season is weighted equally, and episodes *within the same season* are equally weighted.
