Wrapper for asbestos-* collection of components

# To clone from github

    git clone https://github.com/iheos/asbestos.git 

to pull shell of project. This will create directory asbestos

    cd asbestos
    git submodule update --recursive --remote --init
    
to pull all the submodules (parts of build that come from separate github repositories)

Commits from IntelliJ will naturally go to the correct repository

If this is the first time running on this box in development

    cd view
    npm init
    npm install

to update the Javascript dependencies

    npm run serve
    
in a terminal to start UI in development mode. Do this from the view directory.
