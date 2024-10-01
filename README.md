# GPU_Parallelization_of_Matrix-Matrix_Multiplication

Using GPUs in Python

## Getting started

* You need to request a *T4* node on the cluster. Don't forget that you need to add **--gres=gpu** to your srun command.
* Reminder: on the *T4* nodes you need to load a different version of Python, and if it is the first time you are running on a *T4* node, then you need to first load the correct compiler.
* **Note:** You may find at times that your request for a *T4* fails.  This is likely due to there not being available resources in the cloud. I have found that getting a *T4* nodes is most liekly to happen in mornings, evenings, and weekends.

The FIRST time ever that you are on a *T4* node:

Run these command the first time you use a *T4* node. The next time that you need a *T4* node, these commands DO NOT need to be ran:
1. spack load gcc@9.5.0
2. spack compiler find

 

EVERY time you want to run Python and Jupyter-Notebooks:

1. Request a *T4* node:
2. spack load python@3.10.7
