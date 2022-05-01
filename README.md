# Creating interactive charts in Python
The objective of this project is to explore and write a guide to create interactive visualizations using Python, specifically, Panel and hvPlot libraries. To do so, the data used for this project explore Pokémons and Pokémon sales.

A final guide was published on Medium: ["Guide to creating interactive visualizations using Python"](https://levelup.gitconnected.com/guide-to-creating-interactive-visualizations-in-python-78f79ffc7d61).

A final interactive dashboard is deployed on [Heroku](http://pokeviz.herokuapp.com/Dashboard).

<br>

![Image of Dashboard available on Heroku](https://github.com/pcmaldonado/PokemonDashboard/blob/main/plots/Dashboard.png)


## Data
In this project I use data available on [Kaggle](https://www.kaggle.com/datasets/mariotormo/complete-pokemon-dataset-updated-090420) and on [Wikipedia](https://en.wikipedia.org/wiki/Pok%C3%A9mon_(video_game_series)#Reception).

* `pokedex.csv` contains data about Pokémons available on [Kaggle](https://www.kaggle.com/datasets/mariotormo/complete-pokemon-dataset-updated-090420) *provided under a [CC-BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/) License*
* `game_sales.csv` contains data about Pokémons sales, which was scraped from Wikipedia (see `sales_data.ipynb`) *available under the {[CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) License*


## Project Files
* `Dashboard.ipynb` is a Jupyter Notebook containing the python code used for this project.
* `Procfile` is a file needed to deploy the dashboard on Heroku
* `Requirements.txt` lists the libraries used in this project (needed for deployment on Heroku)
* `Runtime.txt` contains the python version used in this project (needed for deployment on Heroku)
* `thimo-pedersen-dip9IIwUK6w-unsplash.jpg` is an image file used on the final dashboard
