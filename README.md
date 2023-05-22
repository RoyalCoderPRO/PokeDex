# POKEDEX

#### Video Demo:  <https://youtu.be/Rhk1kWNP9nw>

#### Description: # Pokémon Pokedex

This is a Python script that allows you to create and manage your own Pokémon Pokedex. You can add new Pokémon to your Pokedex, view the list of Pokémon you have added, and interactively navigate through the menu options.

## Prerequisites

- Python 3.x
- Requests library (`pip install requests`)

## Usage

1. Clone the repository or download the script `pokedex.py` to your local machine.
2. Install the Requests library by running `pip install requests` if you don't have it installed already.
3. Open a terminal or command prompt and navigate to the directory where the script is located.
4. Run the following command to execute the script:


   python pokedex.py


5. The script will display a menu with two options:

   - Option 1: Put a new Pokémon in your Pokedex.
   - Option 2: Check your Pokémon set.

6. Enter the corresponding number for the desired option and press Enter.

   - If you choose option 1, you will be prompted to enter the name of the Pokémon you want to add to your Pokedex. The script will retrieve data about the Pokémon from the PokeAPI and save it in a file called `PokeDex.txt`.
   - If you choose option 2, the script will display the list of Pokémon you have added to your Pokedex.

7. After performing the selected action, you will be asked if you want to add any other Pokémon to your Pokedex. Enter 'Y' for Yes or 'N' for No and press Enter.

8. The script will repeat the process based on your response until you choose to exit.

## License

This script is licensed under the [MIT License](https://opensource.org/licenses/MIT). Feel free to modify and use it according to your needs.

## Credits

- [Github](https://github.com/RoyalCoderPRO) - Aditya Karmokar
- [LinkedIn](https://www.linkedin.com/in/aditya-karmokar-6785751b1/)

This script utilizes the [PokeAPI](https://pokeapi.co/), an open API for retrieving Pokémon data.

## Personal Comments

This took me a little while, and I had intially made it without any abstraction, however, I re-oriented it to have separate functions for utility and passing the conditions for submission. I chose a text log instead of internal storage so that the storage existed beyond the scope of the application. I optimized this program resonably so that it could be used in a larger scale. It actually has applicative purpose, and even if not a particularly unique project, it may be used by those (like me) with low-end devices who would prefer highly lightweight logging of pokemon. The only difficulty I had was to make all std input output reserved to main and one other function to pytest.
