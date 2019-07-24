#If working on own desktop/laptop:
## Create the anaconda environment using the yml file. Please ensure to specify 'conda env create' and not 'conda create'
conda env create -n student_ml_env --file environment.yml python=3.6
## enter anaconda prompt (on windows)
activate student_ml_env
## activate env on linux
source activate student_ml_env

jupyter notebook &
