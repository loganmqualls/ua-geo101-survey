Last login: Thu Jul  7 16:55:09 on ttys000

The default interactive shell is now zsh.
To update your account to use zsh, please run `chsh -s /bin/zsh`.
For more details, please visit https://support.apple.com/kb/HT208050.
(base) Logans-MacBook-Pro:~ lmqualls$ cd Desktop/survey/
(base) Logans-MacBook-Pro:survey lmqualls$ ls
data		output		readme.txt	survey.ipynb
(base) Logans-MacBook-Pro:survey lmqualls$ cd readme.txt 
-bash: cd: readme.txt: Not a directory
(base) Logans-MacBook-Pro:survey lmqualls$ vi readme.txt 


Description:
This notebook was made to visualize the Qualtrics GEO101 lab survey results for the University of Alabama's Department of Geological Sciences.

Folder structure is as follows:

survey_results (repository) --
                            |
                            |-- survey.ipynb
                            |
                            |
                            |-- data/
                            |
                            |
                            |__ output

The survey.ipynb notebook imports the raw Qualtrics spreadsheet that should be located in data. This spreadsheet should be saved as a .csv with "Use Choice Text" selected. Some manually data cleaning is necessary, like making sure all the names are spelled correctly and consistently, making sure there are no spaces after the names, etc. The only input necessary to specify is the survey_file path, if the results are saved under a name other than "survey_results.csv". This notebook visualizes results by question and by TA, making distributions, comparisons, and performance presentations as simple as running a notebook.


