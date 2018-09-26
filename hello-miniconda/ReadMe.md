## miniconda

https://conda.io/docs/user-guide/getting-started.html#managing-envs

cheat sheet
https://conda.io/docs/user-guide/cheatsheet.html

Check to see if a package you have not installed named “beautifulsoup4” is available from the Anaconda repository (must be connected to the Internet):
conda search beautifulsoup4

conda create --name hello-miniconda {optionally do install at end}
Proceed ([y]/n)? y

conda activate hello-miniconda

Install this package into the current environment:
conda install beautifulsoup4


To see a list of all your environments, type
conda info --envs

conda list

