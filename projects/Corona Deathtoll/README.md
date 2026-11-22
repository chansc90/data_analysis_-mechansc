# Telling Stories Using Data Visualization and Information Design

A good graph does more than display numbers: it helps the audience understand them quickly. Design choices such as the chart type, the colors and what to leave out decide whether a reader grasps the message or gets lost in the details.

In this project we work as data journalists writing an article about the coronavirus in December 2020. The goal is to show readers how devastating the virus is, with graphs that work well on a mobile device. Using Matplotlib's object-oriented interface, we apply several design principles step by step:

* **Familiarity:** use a simple horizontal bar plot of the top 20 countries by death toll, because readers already know how to read it.
* **Maximizing the data-ink ratio:** remove spines, ticks and redundant labels so the attention stays on the data.
* **Direction of reading:** move the tick labels to the top, left-align the country names and use a muted color for the axis labels.
* **Storytelling:** turn static facts into a data story that shows change over time, using a grid of line plots for the US death toll (March to December 2020), highlighted periods and a progress bar for the cumulative deaths.

## Data Files

This project uses the following data files:

* `top20_deathtoll.csv`: Total COVID-19 deaths for the top 20 countries (collected from [Worldometer](https://www.worldometers.info/) on December 8, 2020)
* `covid_avg_deaths.csv`: Monthly new COVID-19 deaths in the United States during 2020

## Instructions

1. Download or clone this repository.
2. Ensure that the data files are located in the `Data/` directory.
3. Open the Jupyter Notebook `Telling Stories Using Data Visualization and Information Design.ipynb` and run the cells to reproduce the analysis.

## Project Notebook

You can also directly view or run the analysis in the [Jupyter Notebook](https://github.com/chansc90/data_analysis_-mechansc/blob/main/projects/Corona%20Deathtoll/Corona%20Deathtoll%202020.ipynb)
