# Loadingbar-Download-simulation
##Download Progress Bar using tqdm
This is a simple Python script that demonstrates the use of tqdm to create a progress bar for a download. The script also simulates a download by using a list of files and adding a delay to each file download.

##Requirements
- Python 3.x
- tqdm
- alive_progress
##Installation
- Clone the repository or download the script.
- Install the required packages using pip:
```
pip install tqdm alive_progress
```
##Usage
- Run the script using the command:
```
python download_progress_bar.py
```
- Choose an option from the menu:
- Start Downloading: This option will start the download and display a progress bar for each file.
- Changelog: This option will display the version history of the script.
- If you choose the "Start Downloading" option, the script will simulate a download by iterating through a list of files and adding a delay to each file download. The progress bar will update for each file download.
##Customization
- You can customize the list of files by modifying the my_list variable in the script.
- You can customize the delay for each file download by modifying the  wait_time variable in the script.
- You can customize the list of slow files by modifying the slow_list variable in the script.
##Credits
tqdm: https://github.com/tqdm/tqdm
alive_progress: https://github.com/rsalmei/alive-progress
