# youtube_engagement_movie_gross
A look at whether we can use youtube engagement metrics (views,likes,comments) to predict the box office gross of a movie.

Skills demonstrated: web scraping, Api, data cleaning, data analysis, Data visualization.


Questions?/Hypothesis


 1. Can youtube views on a movie trailer be used to predict the future box office performance of the movie?
      
      Views can be used as a predictor of box office performance.
  
 2. Are the likes on the videos in any way correlated to its future performance?
      
      Likes can be used as a better predictor because likes can't be used in ads of video only when the user seeks the video out through search, trending or recommended.
    
 3. Are comments on a movie trailer a Key Performance Index on the movie's performance?
      
      No comment count won't predict the movie gross since comments can mean a movie is controversial (good or bad) or has a rabid fan base that argues in comment section.

  4. Are comments on a movie trailer a Key Performance Index on the movie's performance?
      
      No comment count won't predict the movie gross since comments can mean a movie is controversial (good or bad) or has a rabid fan base that argues in comment section.



Process

Gather the data

Data sources:
    
  1.Box office mojo
  
  2.the-numbers
  
  3.youtube api data on studio channels
    
Explore the data

   1.There are some rows that repeat year from year, movies released at the end of one year appear on both release year and following year.
   
   2.There are rows with empty values

Clean the data

   1.Remove the duplicate movies.

   2.Remove rows with empty value fields.
