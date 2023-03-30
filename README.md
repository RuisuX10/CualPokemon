# CualPokemon

Juego de adivinanza de Pokémon utilizando la API de Pokémon. El juego consiste en mostrar una imagen de un Pokémon aleatorio y pedir al usuario que adivine su nombre. Si el usuario adivina correctamente, su puntaje aumenta en uno y se muestra una nueva imagen de un Pokémon aleatorio. Si el usuario no adivina correctamente, se muestra una nueva imagen de un Pokémon aleatorio pero su puntaje no aumenta.

El código utiliza la función fetch de JavaScript para obtener datos de la API de Pokémon. La función getRandomPokemon obtiene un Pokémon aleatorio llamando a la API de Pokémon con la URL "https://pokeapi.co/api/v2/pokemon?limit=151&offset=0". Luego, selecciona un Pokémon aleatorio de la lista de resultados y llama a la API de Pokémon con la URL "https://pokeapi.co/api/v2/pokemon/" + nombre_del_pokemon para obtener más información sobre ese Pokémon. La función checkGuess verifica si el nombre del Pokémon adivinado por el usuario es correcto o no y actualiza el puntaje y el número de intentos en la pantalla. La función showPokemon se utiliza para mostrar la imagen del Pokémon que se ha seleccionado.

El código también utiliza jQuery para ocultar el contenido del main y pasar al juego cuando se hace clic en el botón "Jugar!". El puntaje y el número de intentos se muestran en la pantalla utilizando variables HTML con id "puntaje" e "intentos", respectivamente.

