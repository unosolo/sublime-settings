# sublime-settings

## Set up your device for using this settings
You can create the repository in the existing sublime text 3 directory of all other Sublime Text devices (aka ~/.config/sublime-text-3/):

```sh
$ git init
$ git remote add origin <repository url>
$ git fetch
$ git reset --hard origin/master
```

With the last line, the existing setting files will be overwritten by those from the repository. If you want your local files to be committed, just make a backup before and copy the files back to the created repository to commit the changes. Or remove the “hard” flag of the reset instruction and merge all changes manually.

## Thanks
I want to thank Andreas Müller for his article [Using Git to sync Sublime Text settings](https://medium.com/@devmount/using-git-to-sync-sublime-text-settings-f70b8dc7a40d), where I took the basic ideas to create this repository for personal use. 
