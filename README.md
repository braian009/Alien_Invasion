# Alien_Invasion
A simple game project, made following the advices, instructions and good practices of the book "Python Crash Course"
The dynamic of the game is based on a ship that has to destroy a fleet full of aliens, once the first fleet is down, a new and faster one appears, simulating a level progression.
The controls are: left and right arrow to move, and spacebar to shoot.
![muestra](https://user-images.githubusercontent.com/104102591/179629753-50d680ed-7600-4fd0-9070-2a4c2fc965a7.png)


## Getting started 
Assuming you have python already in your computer, install pipenv, which is the tool used in this project to create a virtual environment and avoid compabilities issues that may appear with the packages and dependencies. Run in the command line:
```
pip install --user pipenv
```
Clone the repository to a folder of your choice, and in that directory through the command line type the following to install the dependencies:
```
pipenv install
```

Now, to activate the virtual environment, run:
```
pipenv shell
```
And finally, run the game:
```
python alien_invasion.py
```
