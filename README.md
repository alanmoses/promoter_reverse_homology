# promoter_reverse_homology
Learn interpretable motif-based encoders using reverse homology and embed promoter sequences using phylogenetic averaging (RHIEPA)


###copyright Alan Moses 2021-2025
###permission to use and copy is granted for research purposes only
###software provided as is with no warrantee of any kind

These are the codes to infer motif-based RHIEPA representations directly from genome sequences. The test data provided is only to verify that the code is running correctly. The full training data sets are available for download seperately.

Step 0. set up the python environment. conda .yaml files are provided for CPU and GPU (tf_cpu.yaml, tf_gpu.yaml)

Step 1. Learn a motif-based encoder usinf reverse homology

 $ python promoter_reverse_homology.py test_data/

Step 2. compute the RHIEPA representation for the sequences

$ python compute_promoter_rep.py promoter_rh_interpretableN256L15_f4_b256_final_weights.h5 test_data/

Additional information (output file names, etc.) can be found/set in plain text at the beginning of each of the python files

