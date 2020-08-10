# Create a GitHub repository

Instructions for github repository go here

# Create a Gitpod Workspace

<img style="width: 400px" src="https://github.com/OperationSpark/fsd-setup/blob/master/create-workspace-gitpod.png?raw=true">

1. Go to: <a href=gitpod.io>gitpod.io</a>
2. Scroll down to "Get Started" (see above)
3. Paste your GitHub url in the space to create a workspace
4. Pin the workspace (see below)

-- insert pin workspace image here -- 

# Install your projects

With your workspace open, find bash terminal and enter these commands (see above)
* `git clone operationspark/setupScript`
* `npm install -g opspark`
* `chmod +x script/setup.sh`
* `./script/setup.sh`

Enter your username and your password.

# To Preview Your Code
Install Live Server
Right Click on `index.html` of the project you are working on and select "Preview with Live Server"

# To Share your Code

Workspace --> Share Running Workspace

# To Push Code

Go to: gipod.io/access-control

<img style="width: 400px" src="https://github.com/OperationSpark/fsd-setup/blob/master/authorize-github-push.png?raw=true">

Check the write public repos box (see the picture above below)

Return to your workspace and find the bash terminal.

Then, enter these commands
`git add .`
`git commit -m "describe your changes here"`
`git push`
