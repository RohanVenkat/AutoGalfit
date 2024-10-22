The executable to use is called "AutoGalfit". This is a wrapper software around Galfit which performs the following additional features

1. Can automatically run galfit an arbitrary number of times (the general recomendation for a monte-carlo procedure like this is 1000-10,000 trials)
2. Randomly adjusts each pixel value in the image based on the inputted weight map
2. Randomly adjusts the initial guesses (Galfit has a tendancy to care about the guess provided in the feedme file)

Additionally, we provide our code which is in the file called "AutoGalfit_SC". Feel free to let us know if you have any suggestions, my email is rvenkatphys@gmail.com, thank you!