# BayWheels Data Exploration Project

This project explores the data for a bike sharing company BayWheels (Ford GoBike) for the years 2017 and 2018 'Bay_Wheels_Project_Part1'. The key visualisations are put into a presentation 'Bay_Wheels_Project_Part2'. The data is gathered from websites hosted online.

## Installation

To run this code locally Python 3 and Jupyer Notebook both need to be installed. Anaconda will install both.

Anaconda is available for Windows, Mac OS X, and Linux. You can find the installers at https://www.anaconda.com/download/ and the installation instructions [here](https://docs.anaconda.com/anaconda/install/).

Once Anaconda is installed update all the packages. This can be done by running the following code in the Anaconda Prompt:

```
conda upgrade --all
```

Clone the GitHub repository and open the notebook.

```
git clone https://github.com/ezeahunanya/baywheels_data_exploration.git
```

To run the presentation, run the following code in command line:

```
jupyter nbconvert Bay_Wheels_Project_Part2.ipynb --to slides --post serve --template output_toggle
```
