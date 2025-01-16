# Weekly EDS 232 Labs

This repository houses the weekly labs for EDS 232, Environmental Machine Learning course at the Bren School of Environmental Science &amp; Management. Follow the instructions on the course website (or below) to fork this repository and pull the weekly labs.  



## Initial Repository Setup

### Step 1: Fork the Repository

1. **Navigate to the following Repository**: https://github.com/annieradams/EDS232-labs

2. **Fork the Repository**: Click the "Fork" button located at the top right corner of the page. This creates a copy of the repository in your GitHub account.

## Step 2: Clone Your Fork

1. **Copy the URL of Your Fork**: On your fork's GitHub page, click the "Code" button and copy the URL provided.

2. **Clone the Repository**: Start a new Jupyter Lab Session on Workbench 1 and run the following command (replace `URL_OF_YOUR_FORK` with the URL you just copied):
   
`git clone URL_OF_YOUR_FORK`


### Step 3: Configure your remote branch

1. **Add upstream remote branch.**: Change your directory to the new repository. Once there, copy the following line into your terminal:


`git remote add upstream https://github.com/annieradams/EDS232-labs.git`

**To verify the new upstream repository you have specified for your fork, type**

`git remote -v `

*You should see the URL for your fork as origin, and the URL for the upstream repository as upstream.*



## Weekly Fetching to get new labs

To ensure you have the latest lab materials each week, make sure you are at the correct directoy and copy the following code in the terminal: 


`git pull upstream main  # or master if the main branch is named master`

This command will fetch the latest updates from the upstream and merge them into your current branch.


#### You are now ready to start working on this week's lab!! 

