
# IMDB Movies Analysis


   ## Project Goals
   The objective of this case study is to conduct an extensive analysis of a movie database comprising various tables to explore database relationships, analyze data distribution, and provide actionable recommendations for content production and business strategy.
   
## Database Structure and Relationships
## Tables and Connections
   ### Director Mapping:
  *Connected to Movies by movie_id*
  
  *Connected to Names by name_id*
  
   ### Genre:

  *Connected to Movies by movie_id.*

  ### Movies:

  *Connected to Genre, Ratings, Director Mapping, Role Mapping by movie_id.*

  ### Names:

  *Connected to Role Mapping and Director Mapping by name_id.*
  
  ### Ratings:

  *Connected to Movies by movie_id.*

  ### Role Mapping:

  *Connected to Movies by movie_id.*
  
  *Connected to Names by name_id.*

