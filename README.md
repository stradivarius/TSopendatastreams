# TS Open Datastreams
This repository includes an open dataset of IoT datastreams extracted from the ThingSpeak cloud platform.

Each dataset is already split into TRAIN and TEST sets, obtained through Stratified split.

We built the dataset "ThigspeakEU", if you make use of it, please cite: Montori, Federico, Kewen Liao, Prem Prakash Jayaraman, Luciano Bononi, Timos Sellis, and Dimitrios Georgakopoulos. "Classification and annotation of open internet of things datastreams." In International Conference on Web Information Systems Engineering, pp. 209-224. Springer, Cham, 2018.
The other two datasets have been adapted from existing datasets as a term of comparison.

Each dataset is comma-separated, each line corresponds to a single data record with the following structure:
- Column 0 is the database ID
- Columns 1-7 are metadata in words (fields are empty for Swissex and UrbanObservatory datasets)
- Column 8 is the class label
- Columns 9-end are the numerical data points (the sensor measurements)

For any question, drop an e-mail to federico.montori2[AT]unibo.it
