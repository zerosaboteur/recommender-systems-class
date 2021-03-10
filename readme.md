# Recommender Systems class

Department of Mathematics and Computer Science, Adam Mickiewicz University, 2021

Author: Piotr Zioło

## Preparing your computer

1. Install [Anaconda](https://www.anaconda.com/products/individual) with Python 3.8.


2. Install [Git](https://git-scm.com/downloads).


3. Install [PyCharm](https://www.jetbrains.com/pycharm/) (community version).


4. Fork this repository to your GitHub account.


5. Go to a chosen folder on your machine where you want to have a local copy of the repository. Right-click in the folder and from the context menu choose "Git Bash Here". Run the following command to clone the forked repository on your GitHub account to your local machine:

	<pre>git clone <i>your_repository_address_which_you'll_find_in_your_github</i></pre>

	Alternatively, open Git Bash (installed with Git), change the path to the folder where you want to have a local copy of the repository, execute the above command.


6. In Git Bash open the repository folder and type:

		jupyter notebook

	A new tab with Jupyter Notebook should open in your browser.


7. In Jupyter Notebook open jupyter_test.ipynb.


8. Click on the first cell and hit shift+enter. The first cell should get executed properly. Do the same for all other cells (you can continuously hit shift+enter until you execute all cells).

	The most common error you may encounter is "ImportError: No module named...". In such a case:
	
	- copy the package name,
	
	- close the tabs with Jupyter and in Git Bash where you started Jupyter Notebook click ctrl+c,
	
	- run the following command:
			pip install package_name
			
	- the package should get installed successfully,

	- after that you can open Jupyter Notebook again and test if it works now.


9. After you finished a piece of code in your repository, run the following commands in Git Bash (in the repository folder):

		git add -A

		git commit -m "Commit message"

		git push

	The first command adds all changes and new files for the next commit. The second command commits your changes (it's a kind of a checkpoint/save to which you can later return if need be). The third one sends your commit to GitHub (or any remote repository, in general). 
	
	**Convention:** For your commit messages use imperatives, e.g. "Do this, do that". Try to give informative one-liners.


10. (Optional) Set up your Git Bash to make it look as below:

	![Git Bash](img/git_bash.png)

	Copy .bash_profile and git-prompt.sh files from the git_configuration folder from this repository to your user folder (tested on Windows 10; on other systems they may need to land somewhere else).


11. (Optional) Set up SSH on your machine for easier access to your GitHub repositories through Git. You can find tutorials on the internet how to do that.

	To additionally add an automatic prompt for SSH password in Git Bash, copy a script similar to .bashrc from the git_configuration folder to your user folder. In the file change the name of the key (in the given file there are two given; you can just leave one).


**In the case of any problems, consult your best friend - [StackOverflow](https://stackoverflow.com/)**.

