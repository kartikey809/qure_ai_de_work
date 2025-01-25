# Setup and Execution Guide

-1) **Clone the repository** to your local machine and navigate into the project directory .

-2) **Install the required dependencies** listed in `requirements.txt` by running `pip install -r requirements.txt`.

-3) **Execute the Notebooks in Sequential Order**:

3.1) **`data_ingest.ipynb`**: Ingests raw DICOM files and stages them into a logical directory structure. Run with `jupyter notebook data_ingest.ipynb`. 

3.2) **`etl_process.ipynb`**: Processes the staged data and populates relevant database tables. Run with `jupyter notebook etl_process.ipynb`. 

3.3) **`eda_viz.ipynb`**: Performs Exploratory Data Analysis (EDA) and visualizes the data in the database tables. Run with `jupyter notebook eda_viz.ipynb`.


