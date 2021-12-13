# Space-Time-Cube-3D and 4D visualization
## Studies on Human Behaviour - Course  Project
Geovisualization of Spatio-temporal data is a very promising keynote, especially for social sciences. It is possible to use a space-time cube to divulge activity, travel patterns of different genders, racial groups, non-employees, etc., and all the information can be related to urban planning, transportation,location-based services, and many other fields dealing with individual geo-data.In this work, I used the GPS data that describe the movements of 3 subjects and Time-diaray data, data collected from the 3 subjects through the ilog-mobile application. 
## Dataset 
Here is the [Link](https://drive.google.com/file/d/1CfC9VytolQJkGfcluuuo5vmLKWrj-XCq/view?usp=sharing) for the Two datasets.

## Dependencies
The ptoject uses:
- Python v3+
- Numpy v1.20.3
- Pandas v1.3.4
- Geopandas v0.10.2
- Plotly v5.4.0

Before executing the notebooks the following  dependencies must be installed in your Python's environment

```bash
!conda install --channel conda-forge cartopy 
!pip install pandas keplergl movingpandas 
!pip install topojson 
!pip install geojson
!pip install -U kaleido
!pip install scikit-image```

or you can Create your conda environment and install dependencies from the requirements.txt file accordingly

```bash
conda create -n "enviroment-name" python=3.6
```

and install the dependancies.
```bash
pip install -r requirment.txt
```

## Running the  Project noteooks

After installing all dependencies in your Python's environment, execute the desired script using below commands.There are different ways to run the notebook. Here simpler way have been presented.

* Step 1: Change the working directory of the project to the project folder
* Step 2: run the following command on the cmd
```bash
jupyter notebook
```
* Step 3: A browser will pop up with a notebook. If the browser is not press a link on the cmd which has "htts://localhost:" in it. This will open a notebook on a browser.
* Step 4: Now each cell can be run by pressing "SHiFT + ENTER" on your machine
