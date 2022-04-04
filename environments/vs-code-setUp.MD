1. Install VS code

2. Install and Enable extensions like - gitlens, gitgraph, jira, python, YAML, XML, docker, kubernetes, etc.

3. git clone a project / create and empty project(folder) -> Open with VS code.

4. Create conda virtual env using existing YAML enviroment files.
    4.a. change prefix and name in the yml file, before running it.
    4.b. conda env create --file ./enviroments/mleng-environment.yml
    4.c. select conda Python-interpreter from the bottom right corner.
    4.d. Restart the VS code interpreter.

5. OR create a fresh virtual ENV and install required libraries:
    5.a. conda create env <name>
    5.b. pip install <package-name>
    5.c go to Settings >> Search "venv Path"
    5.d. Paste the path to your Virtual conda ENV.
    5.e. select the desired conda python-interpreter from botton right.

5. test run any file.
    5.a. if fileNotFoundError comes due to relative path, try this:
        5.a.i. Go to settings. Search in settings -> "execute in File Dir"
        5.a.ii. tick this checkbox. restart the VS code interpreter.

6. add new changes in the repository. -> commit -> push your first test commit to Github.

DONE -----
