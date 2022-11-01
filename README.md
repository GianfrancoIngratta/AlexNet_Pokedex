# AlexNet_Pokedex
The repository has the scope of classifying pokémon images, taken from the first generation ever released to the public, using an image recognition algorithm based on a convolutional neural network (CNN): the [AlexNet] (https://en.wikipedia.org/wiki/AlexNet) architecture.

## Pokémon Images Dataset
The basic idea is to feed the net with a set of known pokémon images and eventually test the identification capabilities of the algorithm. The chose dataset embeds only first generation pokémons (i.e. the first [Pokédex] (https://en.wikipedia.org/wiki/List_of_generation_I_Pok%C3%A9mon)), and the images were taken from a public [dataset] (https://www.kaggle.com/datasets/thedagger/pokemon-generation-one. Inside the dataset, the image distribution in not uniform. We decided to use only the images of the pokémons with the higher number of images, which were Mewtwo, Pikachu, Charmander, Squirtle and Bulbasaur. 

## Run the notebook
To run the notebook:
- Add the notebooks to Google Drive and run from there;
- Use `githubtocolab` website starting from the Github repository;
- (Not recommended) Download locally all the files and run the notebooks on personal machine. 

## Features and test to be added in future

- Run more epochs to study the accuracy and the epoch 
- Try to populate with more images the pokémons with fewer entries;
- Change the pokémon list to check different train sets;
- Repeat the previous points until the results are promising;  
- Add a new dataset with newer generations;
- (Not too soon) Train the whole pokédex to the Net;
- (Not too soon) Try to implement a feature to select input images chosen by the user.