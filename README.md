# Test from local repo directory
START USING GH CLI
❯ brew install gh

Add the gh to the ~/.zshrc plugins

❯ gh repo create test-gitignore

Welcome to GitHub CLI!


❯ gh auth login

? What account do you want to log into? GitHub.com <br />
? What is your preferred protocol for Git operations? HTTPS <br />
? Authenticate Git with your GitHub credentials? Yes <br />
? How would you like to authenticate GitHub CLI? Paste an authentication token <br />
Tip: you can generate a Personal Access Token here https://github.com/settings/tokens <br />
The minimum required scopes are 'repo', 'read:org', 'workflow'. <br />
? Paste your authentication token: **************************************** <br />

❯ gh repo create test-gitignore --public

✓ Created repository Misk77/test-gitignore on GitHub

Now we having a new repo on our personal account
Verify the creation:

❯ gh repo list | grep test

Delete a repo

❯ gh repo delete test-gitignore

CREATE THE CONTEXT OF NEWLY CREATED REPO


# Create a new repository on the command line
❯ mkdir test-gitignore.repo && cd $_

touch README.md

git init

git add README.md

git commit -m "first commit"

❯ git remote add origin git@github.com:Misk77/test-gitignore.git

❯ git push -u origin master

 

# Push an existing repository from the command line

 

git remote add origin git@github.com:Misk77/test-gitignore.git

git push -u origin master



