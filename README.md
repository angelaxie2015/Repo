# Senior Project
This repository is created for my senior project which is a 40-hour-long internship with the CTS-IT group at UF. In this repository, I will demonstrate the steps I've used in creating branches and developments through the gitflow workflow. 

## Step One
### Creating a New Repository
1. Navigate into your Github account. 
2. Click on __NEW__ on the top left corner and create a repository. 
3. Select the option __Initialize this repository with a README__
4. Select the option __add a license__ *The one I chose was Apache License 2.0*

## Step Two
### Adding Files
*It is essential to have a README.md, a License file, an AUTHORS file, and a CHANGELOG file. README is a description of the repository and steps associated with the repository. CHANGELOG is for documenting releases (changes).*
1. Clone the ropository. 
2. Open up Terminal. 
3. Within your Terminal:
	* a. Clone the repository into your terminal: ```git clone``` + paste the repository cloned.
	* b. Go in to the repository file: ```cd``` + name of repository cloned. 
	* c. Create the AUTHORS file and the CHANGELOG file: ```touch AUTHORS``` and ```touch CHANGELOG```
	* d. Edit the files using nano: ```nano AUTHORS``` and ```nano CHANGELOG``` use __Ctrl-O and Ctrl-X__ to quit nano. 
	* e. Add and commit the changes: ```git add AUTHORS``` ```git commit -m "add AUTHORS file"``` and ```git add CHANGELOG``` ```git commit -m "add CHANGELOG file"```
	* f. Push the changes into the remote repository: ```git push```
4. View the results on Github. You should notice that two more files named CHANGELOG and AUTHORS are created. 

## Step Three
### Working in the develop branch and the feature branch. Add a new feature to the product. 


