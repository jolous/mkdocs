Create a repository on GitHub. Then in your terminal initialize the local Git for your documentation.

    git clone git@github.com:####
    cd ####

## ** Give permission to your account **

    ssh-keygen -t rsa
    more /Users/chelsea/.ssh/id_rsa.pub

Copy the output and paste it inside `settings`, then click on `SSH and GHG Keys` on your GitHub account. 

## ** Upload the files on GitHub**

    git add .
    git commit -m "initial commit"
    git push origin main 

## ** Deploying the Documentation to GitHub **

    mkdocs gh-deploy

Copy the URL and paste it in your browser.