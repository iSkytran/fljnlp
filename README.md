# Twitter Hate Speech Analysis Against Japanese Minorities

A study into toxic tweets toward Japanese minorities using `snscrape` and `bert-japanese-base`. Done as a final project for FLJ 351 at North Carolina Study University during the Spring 2023 term.

The associated paper write-up can be found at [final_project.pdf](final_project.pdf).

This repository contains the necessary code to recreate the results found in the paper. The Juypiter notebooks in [scrapers](scrapers) is used to scrape data from Twitter. [bert.ipynb](bert.ipynb) is used to train the model. [classify.ipynb](classify.ipynb) and [classify_by_date.ipynb](classify_by_date.ipynb) are used apply to model to the scraped data. [plot_generation.ipynb](plot_generation.ipynb) is used to create the graphs from the classified data.
