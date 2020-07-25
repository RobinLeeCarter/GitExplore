If Windows, open Anaconda Prompt else open terminal

Optional, check and upgrade conda
```
conda --version
conda upgrade conda
```
-- optional update python
```
conda update python
```
Create environment called "Basic" by default and use your path to environment.yml
```
conda env create --name basic --file GitExplore/environment.yml

conda activate basic

conda list

conda deactivate
```
