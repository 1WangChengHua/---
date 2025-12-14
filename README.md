# DSI\_codes
Codes for LIAO Yishen,WANG Chenghua, "A Disentangled Environmental Cognition and Navigation Model Based on the Entorhinal-Hippocampal Circuit"

## Dependency
We used a UNIX environment (ubuntu 20.04), a GPU (NVIDIA GeForce RTX 3060) with CUDA 12.1, Python 3.10, and following Python libraries:
numpy 1.23, scipy 1.10, nltk 3.7, gensim 4.3, networkx 2.8, cupy 12.0, matplotlib 3.6, pygraphviz 1.9, pandas 1.5, scikit-learn 1.2.,pandas 1.5.2,torch 2.8.0

An environment of Anaconda/Miniconda is given by a file `env_DSI.yml`.

`conda env create -f env_DSI.yml`

`conda activate DSI`
## DSI
Executing the `bash batch_all_with_finetune.sh` command in the directory will output the navigation data results before and after calibration; subsequently, executing the `bash batch_finetune_with_compare.sh` command allows the calibration module to be run independently, yielding new navigation data results.
