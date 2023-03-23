# Currency-Converter

A currency converter app is a mobile application designed to convert one currency into another. With this app, users can easily convert currencies from one country to another, making it an essential tool for anyone who travels frequently or deals with foreign currencies. Currency converter apps typically use the current exchange rates to perform the conversions and can be used to convert any major currency in the world.

## Instructions to run the game

* Open the Github repository where the game code is hosted.

* Click on the green "Code" button and then select "Download ZIP" to download the code as a ZIP file.

* Extract the ZIP file to a folder on your computer.

* Open a command prompt or terminal window and navigate to the folder where you extracted the code.

* Type python ```currency-converter-project.py``` and press Enter to start the game.

* Follow the prompts to play the game.

## Functionality of the code

* The first line imports the requests module, which is used to make HTTP requests to the exchange rate API.
* The next three lines import the necessary modules from tkinter for creating the user interface.
* The ```RealTimeCurrencyConverter class``` is defined, which contains a constructor method that initializes the currency conversion rates and a ```convert()``` method that performs the actual currency conversion.
* The ```App class``` is defined, which inherits from the Tk class and contains the GUI components.
* The constructor of the ```App class``` initializes the ```GUI components```, including ```labels```, ```entry fields```, ```dropdown menus```, and a ```button```.
* The ```perform()``` method of the ```App class``` is called when the ```Convert button``` is clicked, which retrieves the input values and calls the ```convert()``` method of the ```RealTimeCurrencyConverter class``` to perform the currency conversion.
* The ```restrictNumberOnly()``` method is defined to restrict the input in the amount field to only numerical values and a decimal point.
* The ```main()``` function instantiates an object of the ```RealTimeCurrencyConverter class```, passes it to an object of the ```App class```, and starts the main event loop using the ```mainloop()``` method.
