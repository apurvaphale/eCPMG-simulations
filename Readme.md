# Analyzing sub-millisecond timescale protein dynamics using eCPMG experiments

## Pre-requisites
* Any OS running Mathematica

## Step 1: Data generation
1. Use the BM_data_generator.nb code to generate the synthetic CPMG data 
2. Check the input parameters: kex, pB, csd, magnetic fields, R20 and the nucpmg points to be simulated
3. This notebook creates a one dataset each for both the magnetic fields.
4. Make sure that the output directory updated
5. You can set up multiple replicates if needed (differences in datasets will arise due to the introduced stochastic noise)


## Step 2: Data fitting
1. Use LM_and_BM_fittings.nb
2. Check and update the input directory 
2. Make sure magnetic field and tcp values are consistent across both the codes
3. Check the initial fitting estimates for both LM and BM models

### Contact us
For any clarifications or issues with the notebook, raise an issue or reach out to at this email 
`phale[dot]apurva[at]gmail[dot]com` or `kalyan[dot]chakrabarti[at]krea[dot]edu[dot]in`