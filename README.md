# CS598 - DLH Submission
## By
1. **Aryan Kukreja**
2. aryansk2@illinois.edu
3. UIN: 652936393

## Draft Rough Submission
1. [DL4H_Team_27.ipynb](https://github.com/ABusyProgrammer/CS598-DLH/blob/main/DL4H_Team_27.ipynb) contains the Jupyter Google Collab notebook with my draft.
2. [dl4h_team_27.py](https://github.com/ABusyProgrammer/CS598-DLH/blob/main/dl4h_team_27.py) contains the Python pure-code verson of the above notebook. Same thing.
3. [mimic-iv-patient-split.json](https://github.com/ABusyProgrammer/CS598-DLH/blob/main/mimic-iv-patient-split.json) is a JSON file taken from the paper's github repo that can be used to split the data.
4. A requirements.txt file is also passed in, although it is optional if you are running the Jupyter notebook, as the `pip install` instructions are located in there itself. 

## Notes
1. See the formal report here: https://colab.research.google.com/drive/1bmM1wJxqJMKpM7Ebie5b2C6LmB0BAMuZ#scrollTo=vo-VAhKtwMuV
2. The code here is an alternate way of running my implementation (still in draft phase). A lot of the code is currently re-used from the paper's code itself, however, re-writes have taken place to optimize it where possible.
3. The dataset used is `host/patients.csv` from the MIMIC-IV dataset. Since I am still pending on access (I am supposed to get it by the end of the coming week), I am relying on the free subset provided on [this site](https://physionet.org/content/mimic-iv-demo/2.2/hosp/#files-panel), under `patients.csv.gz` (which I extracted using 7Zip on Windows 11).
4. I unfortunately was not able to get the code in a fully operational state, due to the data and and some issues with getting the `pip install` dependencies to work. Most issues have been sorted, and should be cleared in time for the final submission. 
