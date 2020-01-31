# git-tools

Copy files to a directory that is inside your path and make sure they are executable. Open new shell and they are available as git commands.

Add to by path by setting this in your `.bash_rc` or `.bash_profile` or `.zshrc`

    export PATH=~/git-tools:$PATH

## Show unpushed branches

    zoidberg@futurama:data (feature-xyz)$ git unpushed
    6c3102c (HEAD, feature-packagesbundles) newline removed

## Iterate over all .git subdirs and do something

    zoidberg@futurama:data (feature-xyz)$ git forall log --oneline
    6c3102c (HEAD, feature-packagesbundles) newline removed

## Track all branches and update

    zoidberg@futurama:data (feature-xyz)$ git fetch-all
    Branch 0.3 set up to track remote branch 0.3 from origin.
    Branch 0.4 set up to track remote branch 0.4 from origin.
    Branch 0.5 set up to track remote branch 0.5 from origin.
    Branch 0.6 set up to track remote branch 0.6 from origin.
    Branch 0.7 set up to track remote branch 0.7 from origin.
    Branch 0.8 set up to track remote branch 0.8 from origin.
    Branch 0.9 set up to track remote branch 0.9 from origin.
    Branch 1.0 set up to track remote branch 1.0 from origin.
    Fetching origin
    Fetching origin
    
## push repository with tags

    zoidberg@futurama:data (feature-xyz)$ git tush
    
## Show latest tag

    zoidberg@futurama:data (feature-xyz)$ git forall log --oneline
    beta-2.104.0
