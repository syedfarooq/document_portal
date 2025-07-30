### Create a new project folder
mkdir <project_folder_name>

### Move into the project folder
cd <project_folder_name>

### Open the folder in VS Code
code .

### Create a new Conda environment with Python 3.10
conda create -p <env_name> python=3.10 -y

### Activate the environment (use full path to the environment)
conda activate <path_of_the_env>

### Install dependencies from requirements.txt
pip install -r requirements.txt

### Initialize Git
git init

### Stage all files
git add .

### Commit changes
git commit -m "<write your commit message>"

### Push to remote (after adding remote origin)
git push