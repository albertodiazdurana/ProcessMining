# Process-mining
The following exercise will guide you through a typical transformation and data analysis to prepare data from an IT system for process mining. 
The description is availabe in the file: Process event data for analysis.pdf

## <a name="info">General info</a>
Repository Structure

- 'ADD-Preprocess event data for analysis.ipynb' is the file you will be running in your Jupyter Notebook
- 'Example MIX TYPES.txt' is the data you will be importing in the Jupyter Notebook
- 'packagesADD.yml' are the list of requirements you will be installing in [GetStarted](#req) to be able to run the Jupyter Notebook 
- 'Process event data for analysis.pdf' is the document with the description of the excercise.
- The folder '_images' containes the .png files generated in the notebook



## <a name="req">Get started</a>
### Installation

You will want to have Anaconda installed. More information here: https://docs.anaconda.com/anaconda/install/

The environment has been saved to the file: packagesADD.yml

1. Go to the directory in the commandline where you have placed this repo.

2. This file may be used to create an environment using:
-------------------
$ conda create --file packagesADD.yml
-------------------

This environment was created using the platform: win-64 

3. Activate the enviroment with:
------------------
$ conda activate envADD
------------------

4. Open Jupyter notebook from your envADD active environment through your commandline with:
------------------
$ jupyter notebook
------------------

### Run on local machine

- Activate the environment using 
----------------
$ conda activate envADD
-----------------
- Open the file `ADD-Preprocess event data for analysis.ipynb` and run all cells


### Remarks

- As default this notebook reads a file from a url in the subchapter 4.4.2  Dowloading a csv with the scrapped tweets (a faster workaround!). This is so to save you time.
- You can decide to run the cell in subchapter 4.4.1  Scrapin' Twitter (this could take about 4 hours!). As you might have noticed by now this could take a lot of time! If you decide to take this exciting journey, feel free to uncomment the cells in this chapter and to make sure the cell in subchapter 4.4.2 is commented and not executied. 
- Upon running the cells in 4.4.1 a folder 'penguin' is generated localy where your notebook is running. See the description in this subchapter for more details.
