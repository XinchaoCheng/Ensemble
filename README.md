# Ensemble
In the code file, before runing the training process, please select a specific dataset(defalt is Opptunity79).

The defalt configrition is using GPU with Cuda9.0 and tensorflow-gpu1.9,
if cannot run please updata your Cuda and tensorflow-gpu version.

If only using cpu, please use line 248 in singleLSTM.py to replace line 245 
and line 218 in fusionensemble.py to replace line 217.

In the training, first run the singleLSTM.py
Then run the fusionensemble.py and the result will saved to a txt file for each dataset.
