For the github setup, a new repository was created by Sabastian called Adisa-dev. The repository can be cloned from the following address:
   
    https://github.com/shopadisa/Adisa-dev.git

In order to push commits, ask the administrator (Sabastian) to give administrative priveleges.

One point of caution: be very careful to not commit any changes directly to the master branch. Instead create and check-out your own branch in the terminal using:
    git branch NEW_USER
    git checkout NEW_USER

or equivalently,

    git checkout -b NEW_USER

Push any changes that you make to the files to this new branch using the following command:

     git push origin NEW_USER

Note: If you just type git push, then the remote of the current branch is the default value.
