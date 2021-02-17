var express = require('express');
var app = express();


app.get('/', function(req, res){
	const fetch = require('node-fetch');
	const query = "title";
	const url = "https://api.themoviedb.org/3/search/movie?api_key=c4469ec82d7b9972a39a0c4807473ef5&language=en-US&query=" + query + "&page=1&include_adult=false";
	fetch(url)
	.then(res => res.json())
	.then(json => console.log(json));

	res.send(res.json());
	res.send("Hello world!iiiiii");

	   
});

app.listen(4000);
