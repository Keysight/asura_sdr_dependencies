# Instructions to add new submodules

## Adding submodules
    $ git submodule add <remote-url> <destination_folder>

## Pushing changes
    $ git commit -m "Added the submodule xxx (version: xxx) to the projet"
    $ git push
    
## Updating the submodules
    $ git checkout commit-sha1 # SHA-1 related to the commit that will be the base for submodule
    $ git commit -m "Udating submodule xxx to version xxx"
    
# Extra Information
	In order to add or remove a submodules, the command "$ git rm suddir" should be used to remove some submodule and the command "$ git submodule add <remote-url> <destination-folder>" can be replaced by the edition of .gitmodules files.
