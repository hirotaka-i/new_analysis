# Introduction
This repository may be useful to start a new analytical project

# 1. Clone the folder

```
git clone https://github.com/hirotaka-i/new_analysis.git
```

Cloned files
1. README.md
4. requirements.txt
5. .gitignore

Cloned folders
1. code: code snipets
2. report: summary and reports

In addition, I would add the folders like below

3. data: folder to store the input data (**untracked**)
4. priv: working files only in private repo (**should not be copied in the public GitHub**)
5. temp: temporary files generated from input (**untracked**)

data/temp: These folders are not tracked for 2 reasons - (1) The data can be very big. (2) The data cannot be sharable. If the analysis requires the data in these folders, manual copying is required.

priv: Also not tracked. Congig files etc. 


# 2. Modification
1. Change the folder name as appropriate.
2. Initialize the folder.
3. Connect to the appropriate GitHub repository.
3. Modify files/folder structures as needed.

```
git init
git remote add origin <your remote GitHub repository>
# modify folder/data/etc
git add *
git commit -m 'first commit'
git push origin main
```

# Set up python environment
```
python3 -m venv .venv
source .venv/bin/activate # Mac
python -m pip install --upgrade pip
python -m pip install -r requirements.txt
pip install <package name>
pip freeze > requirements.txt # update the file
```


