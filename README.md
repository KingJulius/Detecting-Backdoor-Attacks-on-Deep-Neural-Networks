# [Detecting Backdoor Attacks on Deep Neural Networks](https://github.com/KingJulius/Detecting-Backdoor-Attacks-on-Deep-Neural-Networks) 

EL-GY-9163: Machine Learning for Cyber-security

## Project Description:
Implemented Pruning Defence learnt in Machine Learning in Cyber Security. The Channels have been pruned in decreasing order of the average activation across the entire validation dataset. Models that have been saved are models when accuracy drops by at least {2%,4%,10%} which is in the repaired_nets folder. 

On top of this, a GoodNet has been designed which combines the bad model as well as thee repaired model for each of the 3 cases and we compare the Accuracy and Attack Success Rate between the pruned models and the good nets that use these models as one half of the inputs. 


## Instructions:

### Step 1: Downloading data 

Download the data zip file 

https://drive.google.com/file/d/15sxgJdO9U6OkMJ4gZ80ur1_Xi1cDp1Da/view?usp=sharing

### Step 2: Extract folder containing data and loading it

Unzip the zip file and upload each file individually on to colab with data being the root folder or Upload the unzipped folder along with its contents to Google Drive (Quicker Approach)

### Step 3: Run Code

## Repo Strucutre

checkpoints folder - contains the weight for the good nets of all 3 cases

repaired_nets folder - contains the repaired models











