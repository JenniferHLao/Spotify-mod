# Spotify-mod
Organizes and breaks down Spotify data set by danceability rating of Drake songs.  

Importing a Spotify data set using the open() command, this program reads line by line through the file using a for loop. Before entering the for loop a list is created to store Drake songs. In each iteration unnecessary information like commas are removed and the line is tokenized into list of substrings split by spaces. Artist, song, and danceability variables are set to specific values of the sub string list created by the tokenization, and then the artist variable is checked to see if it is Drake. If the artist is equla to Drake then a tuple called record is created to store the variables artist, song, and danceability and is then added to the previously initialized Drake list. Using the datum variable the Drake list is then printed by danceability, artist, and song.    

This project was done to utilize big data augmentation and analysis, to test skills in organizing data sets, extracting information, and returning specific values. 
