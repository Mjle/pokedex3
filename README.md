# pokedex3
iOS Pokedex app

Pokedex3 allows you to search for Pokemon by either scrolling, or using a search bar. It allows you to see pokemon's respective images, details, and their evolution details.

This iOS app uses RESTful api provided by (pokeapi)[http://pokeapi.co/]. 

It loads a collectionview to display all the (718) pokemons, not including the mega pokemons. 

When you click on a pokemon, Alamofire makes a get request from the RESTful Pokemon API to pull all the pokemon details we want to display.

