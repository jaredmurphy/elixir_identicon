# Identicon

Command line app to learn more about Elixir. 

## This app
This app generates a png based on a string value given by the user. It creates an identicon based on hex values for each character in the name. After creating the grid and applying color, it creates a file named by the user input. 

## Usage
* Fork this repo
* Make sure you have Elixir and Erlang installed
* Open up the command console on the app with `iex -S mix`
* Run `Identicon.main("Alchemist")` (or whatever name you choose)
* You should see a console response of `:ok`. Close the console.
* You should see your <name>.png file in the current directory
