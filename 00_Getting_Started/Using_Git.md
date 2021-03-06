# Accelerator Simulation Framework
## :notebook_with_decorative_cover: Using Git: A guide to the basics
---

# :computer::earth_africa: Using a web browser
## :earth_africa: Basic Commands
> ### How to edit this file (or similar)
>  - Navigate to the appropriate file: e.g. https://github.com/HaroonRafique/Accelerator_Simulation_Framework/blob/main/00_Getting_Started/Using_Git.md
>  - Ensure that you have permission to edit this file - if not, request permission, **fork** the repository to create your own copy, create your own **branch**, or create your own file
>  - Once open in a browser, in the top right corner of the file box locate the edit button (:pencil2:)
>  - Edit the file using markdown (https://www.markdownguide.org/basic-syntax/)
>  - Add emojis if you're feeling adventurous :robot: (https://github.com/ikatyang/emoji-cheat-sheet#book-paper)
>  - Navigate to the bottom of the page :point_down:
>  - In the **Commit changes** box, enter a commit message (***See style guide for tips on writing commit messages***), and press the green **Commit changes** button :green_square:

---

# :computer::space_invader: Using Linux

## :space_invader: Basic Commands
> ### From the command line
> - **git config** Get and set repository or global options
> 
>       git config -global user.name "[name]" 
>       
>       git config -global user.email "[email address]" 
>     
> - **git init** Create an empty Git repository or reinitialize an existing one
> 
>       git init [repository name]
>     
> - **git clone** Clone a repository into a new directory
> 
>       git clone [url]
>     
> - **git add** Add file contents to Git index
> 
>       git add [file]
>       
>       git add -u  # adds all tracked file changes
>     
> - **git commit** Record changes to the repository
> 
>       git commit -m "[commit message]"
>       
>       git commit -a # automatically stage modified and deleted files, but new files you have not told Git about are not affected
>     
> - **git diff** Show changes between commits, commit and working tree, etc
> 
>       git diff -staged
>       
>       git diff [first branch] [second branch]
>   
> - **git status** Show the working tree status
> 
>       git status
>       
>       git status -uno # don't show untracked files
>       
> - **git pull** Fetch from and integrate with another repository or a local branch
> 
>       git pull
>       
>       git pull origin main # note ~2020 Git chose to change master -> main
>       
> - **git push** Update remote refs along with associated objects
> 
>       git push
>       
>       git diff [first branch] [second branch]    

## :space_invader: Advanced Commands
> ### From the command line
> - **git reset** Reset current HEAD to the specified state (unstages file but preserves contents)
> 
>       git reset [file]
>       
>       git reset [commit]
>       
> :warning: **DANGEROUS:** Discards all history and goes back to specific commmit 
> 
>       git reset -hard [commit]
>       
> - **git rm** Deletes file from directory and stages file for deletion
>       
>       git rm [file]
>       
> - **git log** List versoin history for current branch
> 
>       git log
>       
>       git log ???follow[file]
>       
> - **git show** Shows the metadata and content changes of the specified commit
> 
>       git show [commit]
>       
> - **git branch**  List, create, or delete branches
> 
>       git branch # lists all branches
>       
>       git branch [branch name] # create a branch
>       
>       git branch -d [branch name] # delete a branch
>       
> - **git checkout** Switch branches or restore working tree files
>
>       git checkout [branch name] # switch branches
>       
>       git checkout -b [branch name] # create new branche and switch to it
>
> - **git merge** Join two or more development histories together
> 
>       git merge [branch name]
>       
> - **git remote** Manage set of tracked repositories
> 
>       git remote add [variable name] [Remote Server Link] # connect your local repository to the remote server


## :space_invader: :bookmark: General Tips
> ### Use environment aliases to save time
> - In your .bashrc file or equivalent (you will find this in your home directory):
>     
>       cd
>       vim .bashrc
>     
> or
>   
>       vim ~/.bashrc
> where `vim` is a command line text editor. Try `geany` for a GUI based editor on Fedora.
>      
> - Add the following lines to `.bashrc` to shorten git commands:
> 
>         alias gp='git pull'
>         alias gpp='git push'
>         alias gs='git status'
>         alias gsu='git status -uno'
>         alias ga='git add'
>         alias gc='git commit -m'
>
> - Either restart the terminal / SSH connection, or source (activate) the new .bashrc:
> 
>     source ~/.bashrc
>     
> - From the terminal the following commands can be shortened
> 
>         git status -uno
>         git pull
>         git add file.txt
>         git commit -m '<update>[file]'
>         git push
>     
> to:
> 
>     gsu
>     gp
>     ga file.txt
>     gc '<update>[file]'
>     gpp

---

# Using Windows
- [ ] To Do
