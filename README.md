# LCT Mapping
This is a simple example of how to load and combine spatial data and LCT connection data from NGED's open data portal and plot the data in choropleth maps to visualise the distribution of LCT connections.

## Running the code
The python jupyter notebook is contained in the `dev` directory ([here](https://github.com/isaacflower/LCTMapping/blob/main/dev/LCT_mapping.ipynb)).

The data used in the example is contained in the `data` directory under `data/spatial` and `data/lct`.

## Software Requirements
Install the following into a new Conda Environment. Instructions for how to do this are [here](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).

Python version = 3.11.9

Python Packages:
- ipykernel (Running jupyter notebooks)
- numpy (Array operations)
- pandas (Data analysis)
- matplotlib (Basic visualistion)
- matplotlib-scalebar (Scalebars for choropleth plots)
- geopandas (Spatial data analysis)
- osmnx (Importing OpenStreetMap data)
