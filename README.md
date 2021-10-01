# Web Scraping

This is a collection of projects for web scraping data from various websites: 

Most of the modules are in the format: 
* \<project>_**webscraping**.ipynb, where the data is scraped from the relevant source, and,
* **data**, where the data is stored, generally in .csv format.

This repo is a work in progress and there are many bad practices because I'm still learning. Most of the modules have a lot of my exploratory analysis throughout and are filled with outdated cells that I just commented out after I got whatever I wanted working.

### Code / Dependencies: 

* The code is written in Python 3 (so far). 
* Shared and distributed primarily through Jupyter Notebooks (.ipynb's). 
* Most services depend on [Pandas](https://pandas.pydata.org/) and [NumPy](https://numpy.org/) for data manipulation

#### Installation and Setup Locally:

If you want to create something similar, feel free to use whichever pieces you see fit.

Honestly I copy-pasted the portions of whichever portion of a file I needed from other people, though I suppose you could clone it as well. Either way, you probably should enable a virtual environment:

If you haven't already then you should: 

`mkdir <repo_name, e.g. qs>`, otherwise,

`cd <repo_name>`

`python3 -m venv <virtual_environment_name, e.g. venv>`

`source <virtual_environment_name>/bin/activate`

Using your activated virtual environment (in front of your username in the terminal it should say something like: `(<virtual_environment_name>) <username>@<username>:`, install dependencies: 

`pip install -r requirements.txt`

Then navigate into your directory and launch an individual notebook or the full project with jupyter notebook or jupyter lab: 

`jupyter-lab`