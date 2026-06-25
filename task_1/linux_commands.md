\# Linux Commands Documentation



Command | Description | Observed Output 



&#x20;`pwd` | Prints the current working directory. | `/c/Users/User/Synergy\_TP` 

&#x20;`ls` | Lists directory contents. | `.gitignore task\_1`

&#x20;`ls -la` | Lists all contents, including hidden files, with detailed permissions. | `drwxr-xr-x 4 user user 4096 ...`

&#x20;`cd task\_1` | Changes the directory into `task\_1`. | \*(No output, prompt changes)\* 

&#x20;`mkdir temp` | Creates a new directory named `temp`. | \*(No output)\* 

&#x20;`touch log.txt` | Creates an empty file named `log.txt`. | \*(No output)\* 

&#x20;`echo "Init" > log.txt`| Writes the string "Init" into `log.txt`. | \*(No output)\* 

&#x20;`cat log.txt` | Displays the contents of `log.txt`. | `Init` 

&#x20;`cp log.txt backup.txt`| Copies `log.txt` to a new file `backup.txt`. | \*(No output)\* 

&#x20;`mv backup.txt src/` | Moves `backup.txt` into the `src/` directory. | \*(No output)\* 

&#x20;`rm log.txt` | Removes (deletes) the `log.txt` file. | \*(No output)\* 

&#x20;`grep "requests" requirements.txt`| Searches for the word "requests" in the file. | `requests==2.31.0` 

&#x20;`find . -name "\*.py"` | Finds all files ending in `.py` in the current directory tree. | `./src/hello.py` 

&#x20;`head -n 2 setup\_log.md`| Prints the first two lines of the file. | `# Setup Log` 

&#x20;`tail -n 2 setup\_log.md`| Prints the last two lines of the file. | `git push -u origin main` 

&#x20;`wc -l README.md` | Counts the number of lines in `README.md`. | `24 README.md` 

&#x20;`chmod +x src/hello.py`| Adds execution permissions to the python script. | \*(No output)\* 

