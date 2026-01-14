# End to end machine learning project

## create a new environment

command -> conda create -p [ENVIRONMENT_NAME] python==3.8 -y

-y -> no need to ask fro approval at every stage.

all the libraries that we install will be placed inside this folder.

## activate conda environment

command -> conda activate [ENVIRONMENT_NAME]/

## setup github

- initialize the git -> git init
- add read me file -> git add README.md
- add commit -> git commit -m "first commit"
- get status -> git status
- check out to main branch -> git branch -M main
- add remote repo -> git remote add orgin [REPO_URL]
- push the changes -> git push -u origin main

## setup.py

setup.py file is responsible for creating the current machine learning for any other project as a package and even deploy in pypi.

- -e . inside requiremnts.txt will trigger setup.py whenever the package is installed

## src folder and build the package

- install packages from requirements.tsxt -> pip install -r requirements.txt
