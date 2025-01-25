1. Clone the repsoitory
2.  Install the required dependencies listed in requirements.txt
3.  here are three notebooks that should be executed in the following order:
   1. jupyter notebook data_ingest.ipynb
   2. jupyter notebook etl_process.ipynb
   3. jupyter notebook eda_viz.ipynb

Process Overview: 
data_ingest.ipynb: Ingests raw DICOM files and stages in logical directory
etl_process.ipynb: Processes staged data and populate database tables.
eda_viz.ipynb: Performs EDA and visualizations on the data in tables.
 
