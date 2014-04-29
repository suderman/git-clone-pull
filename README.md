#git-clone-pull

One command to clone or pull a Git repo

## Installation

Open a terminal and run this command:  
`curl git-clone-pull.suderman.io/install | sh`

## Usage

Use just like `git clone`, but always specify the destination directory:    
`git clone-pull https://github.com/robbyrussell/oh-my-zsh.git ~/.oh-my-zsh`

If the repo already exists, it will be updated via `git pull`. However, if the repo already exists locally, it will be cloned.
