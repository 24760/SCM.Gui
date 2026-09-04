# -- -- 

- git subtree add --prefix=Git.Ext https://github.com/247i/Git.Ext  முதன்மை --squash
- git submodule add https://github.com/247i/WinMerge.git 
- git submodule add https://github.com/247i/GitHubDesktop  

# To get all files in submodules
git submodule update --init --recursive

Then git commit all the files added

git submodule update --remote --recursive


When cloning this project:

git clone --recursive https://github.com/UniThamizh/Git-Ext-Merge.git

when making changes to submodules use the following command to update 

git submodule update

if any files inside the submodules changed then first commit them and push them then 
commit the super project. 

