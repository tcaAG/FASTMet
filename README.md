# FASTMet
Python packages dealing with LC-MS/MS based 13C-enrichment and flux calculations 


System requirements:
The code packages present here were developed in Jupyter Notebook in Python 3.8.8 environment. The packages were developed and tested in both iOS (version 12.6.6) and Windows 10 (version 22H2). No other non-standard software is needed to run the code.


Installation guide:
Python and Jupyter were installed according to the instructions provided in the respective sources:
https://www.python.org/downloads/
https://jupyter.org/install


Running instructions:
1. Download the notebooks and associated files into a single folder. All necessary files will be available here.

2. Open and run the notebooks in the following order:

2.1. ‘FASTMet-NA_Correction_EnrichmentCalc.ipynb’ - the outcome of this code is .csv file with a name starting with “Enrichment_from_”. These files will automatically be used in the next notebook.

2.2. ‘FASTMet_FractionalFluxes.ipynb’ - the outcome of this code is 3 .csv files with a named “Output_SteadyState_FractionalFluxes.csv”, “Output_SteadyState_QualityControl” and “Output_SteadyState_AllValues.csv”. This last file is automatically used in the next notebook.

2.3. ‘FASTMet_FractionalFluxes.ipynb’ - the output of this code is 2 .csv file named "Output_SteadyState_FluxesRelativeCS_AllIterations.csv" and "Output_SteadyState_FluxesRelativeCS.csv"

Note: the notebooks in 2.1. and 2.2. have a quick run time (few seconds). The notebook in 2.3. has a run time of ~6min for the specified data set and number of minimization itertions. 

