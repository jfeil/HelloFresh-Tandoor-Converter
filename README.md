# HelloFresh-Tandoor-Converter

Jupyter-Notebook for retrieving all hellofresh recipes and importing them into Tandoor via the API

To make this work, you need to insert your base-url and insert the API key available at <BASE_URL>/settings/#api

This is based on the german HelloFresh version! You need to change the `locale` and `country` in the second cell to e.g. `en-US` and `en` and translate the spice conversion (there is a dict that maps each spice to the ingredients and adds this to the note in all recipes.)

This project might break at any point in the future :) Pull requests are welcome ;)

https://github.com/TandoorRecipes/recipes/

Spices to ingredients from https://github.com/Schischu/hello_fresh_gewuerze <3
