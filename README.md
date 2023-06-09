# Predicting NGO Interventions on Social Media

Repository for the semester project, made by: Korovkin Ivan, Parshikov Tikhon.

Structure:
- Airlines_processing.ipynb: notebook with JSON data processing and feature extension for airlines.
- Banks_processing.ipynb: notebook with JSON data processing and feature extension for banks.
- Combined_models.ipynb: notebook with combined language and features models trainnig and evaluation.
- Data_collecting.ipynb: notebook generating necessary Twarc commands to interact with Twitter API through command line.
- Language_models.ipynb: notebook with language model training and evaluation.
- ML models.ipynb: notebook with basic ML models trainnig and evaluation.
- NGO_processing.ipynb: notebook with JSON data processing and feature extension for NGOs.
- Train_dataset.ipynb: notebook with train and test datasets split for further model trainings.

Link to the drive with datasets: https://drive.google.com/drive/folders/1EUsNuhESJB6UI4_XRnV0yPiV8PCxUB0H?usp=drive_link.
Drive has the following structure:
- JSONs: contains downloaded JSON files for different types of organisations. ICRC data has two files for each organisation with extended tweet data collection(Which was later implemented in other datasets collection, that have only 1 file per org).
- CSV_files: contains processed data of related tweets from JSON files, with extended features.
