# INFOVIS_FirstProject
First project for the course of __Information Visualization__ at _Università degli Studi Roma Tre_. The project is about using JavaScript and D3.js to draw 10 mosquitos. These mosquitos have to move in the drawing board by pressing the "x" key on the keyboard, forming a different configuration (the possible configurations are 10 and they are stored in the JSON file). By clicking on a mosquito with the mouse left button, it's killed and it doesn't move anymore (the mosquito disappears and is replaced by a bloodstain). __It's important to precisely click the black outline of the mosquito with the cursor tip__.

Source of the SVGs used :
- [mosquito](https://www.flaticon.com/free-icon/mosquito_1779542)
- [bloodstain](https://www.flaticon.com/free-icon/spot_519043)

In order to launch this application, open the console, go to the directory where the files are located and use the 
command `python -m http.server` (or `python -m SimpleHTTPServer`), then open the browser and go to `localhost:8000` (or `:3000` or whatever is shown on the commandline).
