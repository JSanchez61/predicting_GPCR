# predicting_GPCR
Make sure you have Anaconda installed.

Run the following commands to create the environment:
conda env create -f environment.yml
conda activate biasnet

Run the following commands to predict GPCR/non-GPCR
python run_biasnet.py --smiles fill_in_smile_here
Example: python run_biasnet.py --smiles ClC1=CC=C(C=C1)C2=NOC3=C2CCNCC3
