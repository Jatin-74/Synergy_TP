\# Setup Log



The following commands were executed via Git Bash to configure this task:



git clone https://github.com/Jatin-74/Synergy\_TP.git

cd Synergy\_TP

mkdir -p task\_1/src task\_1/data

touch .gitignore task\_1/README.md task\_1/setup\_log.md task\_1/linux\_commands.md task\_1/src/hello.py task\_1/data/sample.txt

python -m venv task\_1/venv

source task\_1/venv/Scripts/activate

pip install requests

pip freeze > task\_1/requirements.txt

git add .

git commit -m "Complete Task 1 setup"

git branch -M main

git push -u origin main

