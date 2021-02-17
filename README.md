# oit-backend
express.js appi, consuming TMDB api

Backend stepps:
-settup TMDB account and get api key
play with api using curl
	TMDB had tool in api docs to play with request and here is the url:
	https://api.themoviedb.org/3/search/movie?api_key=c4469ec82d7b9972a39a0c4807473ef5&language=en-US&query=fire&page=1&include_adult=false
	with the only query var that needs to change being query=<search term>

setup express.js
setup api routs
setup logic for making api requests to TMDB developed during curl play
setup filters and processes on data recieved from TMDB
data being returned from backend

setup simple vue.js app
get user search
make api request to backend using user input
recive and display data from backend
