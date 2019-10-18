# HOW_TO_USE_GIT

	1) On your personal GITHUB account [https://github.com/DJRumble] create a new repository
	2) Clone that repositotry to the desired folder from the cmd line| git clone https://github.com/DJRumble/HOW_TO_USE_GIT.git
	3) move to the directory | cd HOW_TO_USE_GIT/
	4) create a read me file to explain what is going on in that repo | echo "# HOW_TO_USE_GIT" >> README.md
	5) manually drag and drop any other content into that directory
	6) Initialise the git repo | git init
	7) Add your content | git add *
	8) Push your content into the local stagging area | git commit -m "first commit"
	9) Connect your remote repo to the stagging area | git remote add origin https://github.com/DJRumble/HOW_TO_USE_GIT.git
	10) Push content | git push -u origin master

At any point use 'git status' to check the status of the repo you are in. 
