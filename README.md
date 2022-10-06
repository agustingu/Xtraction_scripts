# OBU logs extraction
The extraction of the logs file requires:
1. The *platform-tools* folder [link 1](https://uflorida-my.sharepoint.com/:u:/g/personal/agustinguerra_ufl_edu/EZCanbKJZ7tBnFc6kjqEPucBDAh4ZDcPSdEsMDekV2bUZw?e=b9cG4e)
2. Watch the training video [link 2](https://uflorida-my.sharepoint.com/:v:/g/personal/agustinguerra_ufl_edu/Ecu2xO3mWM9DnJiKKHtJ1akBLgOX4V8iCRCYBbKN-cn2zw?e=8w9Leb)


# Connected_Vehicles_Data_Pipeline_Extraction

Data pipeline to extract logs files from On-Board Units (OBU) to .csv files. Make sure you have installed Anaconda and Python before the following steps:
1. Clone the repository to your local machine and open the terminal
2. Create the virtual environment according to .yaml file by running `conda env create -n xtraction_scripts --file logs_extract.yaml`. 
3. Activate the virtual environment by `conda activate xtraction_scripts`.
4. Run the extraction pipeline  by running `python main.py` in the terminal

**Note**: If you want to avoid issues with folder location clone this repo inside the *platform-tools* folder (see fig below).
<img src='https://user-images.githubusercontent.com/54486202/194387091-2b75d278-0da0-493f-9cc6-d5f33d0ba15f.png' width=650/>

[embed]https://github.com/agustingu/Xtraction_scripts/blob/main/notebooks/flow_chart.jpg.pdf[/embed]
