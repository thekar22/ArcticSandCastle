Service using applescript created in automator

	Setup Rails Environment:
	
		r-click directory and choose service
		*creates a new terminal window with 3 tabs navigated to clicked directory
		
			rails c
			
			rails s
			
			empty tab for git interactions
			
*****

How to install/use

Open a terminal window

Navigate to /Users/*your_user_name*/Library/Services 
	cd "~/Library/Services"
	*Note Library is a hidden folder, so you may navigate to this in Finder by pressing cmd + shift + g specifying "~/Library/Services"

Within this directory, create a folder titled "Setup Rails Env.workflow" and navigate to it
	mkdir "Setup Rails Env.workflow"
	cd "Setup Rails Env.worfklow"

Clone my repo into this folder. Open the workflow in automator to edit the script to fit your purposes.