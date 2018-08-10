# Ensemble
In the code file, before running the training process, please select a specific dataset(default is Opptunity79).

The default configuration is using GPU with Cuda9.0 and tensorflow-gpu1.9, if cannot run please update your Cuda and tensorflow-gpu version.

If only using CPU, please use line 248 in singleLSTM.py to replace line 245, line 218 in fusionensemble.py to replace line 217.

In the training, first, run the singleLSTM.py Then run the fusionensemble.py and the result will be saved to a text file for each dataset.
