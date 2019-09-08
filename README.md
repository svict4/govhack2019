# govhack2019

Final (awful) product
https://svict4.carto.com/viz/14b228fb-cf7c-4efa-b9ce-4f40c2a0ee11/public_map

The javascript code used to scrape the startups: https://your.startupstatus.co/map/217
```
var suburb = ""
document.querySelectorAll(".eachone").forEach(function(place) {
	debugger;
	if (place.querySelector(".subrub-name-full").innerHTML != "") {
		suburb = place.querySelector(".subrub-name-full").innerHTML;
    }
	var name = place.querySelector(".map-company-name > span").innerHTML;
	console.log(name + ", " + suburb);
})
```

iPython colab that geocodes everything
https://gist.github.com/svict4/8bbd85a41df1ae508ce4336100a2f2e4


