# Onion Soup
The purpose of this repo is it investigate in a distilled form the Onion Architecture aka "Clean Architecture", "Hexagonal architecture" and "Ports and Adapters Architecture". Focus is on how to work with dependency inversion in practice. Further how to scope tests when working within the Onion Architecture
A summery of architecture the can be found @ [Thoughtworks](https://www.thoughtworks.com/insights/blog/architecture/demystify-software-architecture-patterns) as an introduction but further investigations are necessary.



## Layers
For the purpose of this investigation 3 layers should be sufficient as a stating point. 

The outer layer being the most concrete this could be writing to the console, reading from the file system or using a external api like [JokeAPI](https://sv443.net/jokeapi/v2/), [Chuck Norris facts](https://api.chucknorris.io/)or [The Star Wars API](https://swapi.dev/)

The further layers must be developed in the course of experimentation.

## Language 
It has been decided to implement the exercise in TypeScript because it contains the necessary language constructs ([interface](https://www.typescriptlang.org/docs/handbook/interfaces.html) and [classes](https://www.typescriptlang.org/docs/handbook/classes.html)) to implement the Onion architecture. It's unsure if [Object Types](https://www.typescriptlang.org/docs/handbook/2/objects.html#handbook-content) are needed.
It is also possible to create unittests in TypeScript to investigate the ins and outs of testing.