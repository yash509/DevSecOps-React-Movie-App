# DevSecOps-React-Movie-App


<div align="center">

<img align="center" alt="coding" width="3000" src="https://github.com/yash509/DevSecOps-React-Movie-App/blob/master/DevSecOps%20React%20App%20Deployment%202.jpg">
</div>


API Used:-

Open Movie Database (OMDB) API
Generate API key from : http://www.omdbapi.com/apikey.aspx


API Info:-

Method: GET
Search URL: https://www.omdbapi.com/?s={MOVIE_NAME}&apikey={API_KEY}
Movie Details URL: https://www.omdbapi.com/?i={MOVIE_ID}&apikey={API_KEY}


How It Works:-

Search a movie in the search input
Grabs the movie information from OMDB API.
Information is returned has a JSON object
Using React components to structure data into presentational format
Using CSS to create visually appealing and user friendly application


Docker to use to vuild docker image:-

docker build --build-arg OMDB_V3_API_KEY=<your-api-key> -t movie-app .
