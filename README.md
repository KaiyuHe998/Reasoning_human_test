# If you already have conda on your laptop.

## Step1: Setup environment
```
conda create --name test_env python=3.9
conda activate test_env
git clone https://github.com/MeanStudent/Reasoning_human_test.git
cd Reasoning_human_test
pip install -r requirements.txt
```

## Step2: Run the human_test.py
```
python human_test.py
```

## Step3: Save and send me the files
When finished please save and send me the following files:  
Folder: **log_human_test**  
csv: **human_test.csv**


# If you do not have conda on your device then you need to use:
- github codespace (Recommand): https://github.com/codespaces (120 core hour reset every month which is enough for the project)，
- replit (Recommand): https://replit.com/ (Free with limited comput power)
- binder： [https://mybinder.org](https://mybinder.org/v2/gh/MeanStudent/Reasoning_human_test.git/HEAD)


## Step1 Finish puzzles
- Click **terminal** in the new window and execute the following code to run the puzzles
```
python human_test.py
```
**(run pip install -r requirements.txt if package needed is not installed)**

## Step2 Zip/download and send me the files
Run the following code to zip the log
```
  tar -czvf log_human_test.tar.gz log_human_test
```
Download the following files and send them to me
- zip_file: **log_human_test.tar.gz**
- csv_file: **human_test.csv**


# Or use Colab 
## Setup environment (Run the following code in the first chunk)
```
import os
import shutil
!git clone https://github.com/MeanStudent/Reasoning_human_test.git
os.chdir('Reasoning_human_test')
!pip install -r requirements.txt
```
### You will need to restart the session/kernel after running above code.

## Finish the puzzles and download needed files (Run the following code in the first chunk)
```
!python human_test.py
shutil.make_archive('log_human_test', 'zip', 'log_human_test')
```
When finished please download and send me the following files:  
zip_file: **log_human_test.zip**  
csv: **human_test.csv**


