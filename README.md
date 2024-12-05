# DSC-Capstone-Q1-Project

DSC180A Capstone Project Quarter 1 Project

## New York City Metropolitan Transportation Authority Exploratory Data Analysis

- `MTANotebook.ipynb`: Basic exploratory data analysis on given data, including graph representation conversion, congestion analysis, etc..

### Running locally on MacOS

The following tutorial assumes that the user has properly installed `conda` and `pip`.

1. Download data from google drive: https://drive.google.com/drive/folders/1Z0hTunE9Z-lGkVVIelIJ2nmvX6wCiKjx?usp=sharing

   - Store all the data in a folder called `data`

2. Install necessary packages:

   ```
   git clone https://github.com/DILING69/DSC-Capstone-Q1-Project.git
   ```

   ```
   cd DSC-Capstone-Q1-Project/src/MTA
   ```

   ```
   pip install -r requirements.txt
   ```

3. Move the data folder into the github repository folder

4. Run the Jupyter Notebook for result



## DE-HNN Re-Implementation

- `chip-data-analysis.ipynb`: Contains basic information about the dataset and exploratory data analysis including raw data information, graph representation conversion, connectivity visualization, congestion visualization, etc..
- `dehnn-reimplementation-pipeline.ipynb`: Contains a basic re-implementation of the DE-HNN model, trains and benchmarks its result on processed data.

### Running locally on MacOS

The following tutorial assumes that the user has properly installed `conda` and `pip`

Navigate to `DSC-Capstone-Q1-Project/src/dehnn-reimplementation` and run:

```
pip install -r requirements.txt
```

For exploratory data analysis:

1. Download data from google drive: https://drive.google.com/file/d/1Scq35gvCQvIMrmthGs7MUhc8c1VZ8ZwN/view
2. Decompress the file and store all the data in a folder called `DigIC_dataset`
3. Move the folder to `/DSC-Capstone-Q1-Project/data/`
4. Run `chip-data-exploration.ipynb`

For DE-HNN model:

1. Download cleaned data from google drive: https://drive.google.com/file/d/1vCkeixs4mreSGYcIgLENefdKPf3jaCYp/view?usp=sharing
2. Decompress the file and store all the data in a folder called `processed_data`
3. Move the folder to `/DSC-Capstone-Q1-Project/data/`
4. Open/Run `dehnn-reimplementation.ipynb` for result
