This script is a substitute to `git checkout -b command`, it aims to add your initials in the beginning of the branch name automatically in each branch creating.

#SETUP
1. Download the git-checkout file and past it your git scripts folder. e.g: `/Users/user/Documents/gitScripts`
2. Add the directory path to your environment PATH. For Linux/Mac, you can edit your bash_profile. Add following line in the beginning:
  - export PATH=$PATH:/Users/user/Documents/gitScripts
3. source the file to apply the changes:
  - source ~/.bash_profile
4. Set up your initials in your git config.
  - git config --global user.initials "[YOUR_INITIALS_HERE]"
  - run git config user.initials to check if your initials are properly set.

#USAGE
  $ git-checkout [your-branch-name]
