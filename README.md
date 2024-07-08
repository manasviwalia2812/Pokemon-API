# Pokemon-API
This is a Python script named pokemon.py that retrieves and displays an image of a Pokémon card from the Pokémon Trading Card Game API. Here's a summary of the project:

**Functionality**:

1. The script prompts the user to enter a Pokémon name.
2. It sends a GET request to the Pokémon Trading Card Game API with the entered Pokémon name to retrieve the corresponding card data.
3. The script extracts the image URL from the API response and downloads the image.
4. It saves the image as poke.png in the current working directory.
5. The script uses Matplotlib to display the downloaded image.

**Modules used:**

**'requests'** for making HTTP requests to the API

**'matplotlib.pyplot'** for displaying the image


**Files generated:**

**'poke.png'** - the downloaded Pokémon card image

**How to use:**

1. Run the script by executing python pokemon.py in the terminal/command prompt.
2. Enter a Pokémon name when prompted.
3. The script will display the corresponding Pokémon card image.
