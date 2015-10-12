Your repository link will look like https://github.com/spl-sem/YourName and will already have the necessary folder structure in it.

You should follow the following steps to work with your repository (all commands should be executed on the terminal):

* Go to the folder where you want to keep the local copy of your repository
* Run `git clone <repoLink>`. This will create a folder called `YourName` which will contain your repository.
* Run `cd <YourName>` then `ls`, you should see the different folders there.

Suppose you want to submit the paper review for Oct.19:

* Create your review file "Myreview.pdf" in the Oct.19 folder
* Run `git add Oct.19/Myreview.pdf`
* Run `git commit Oct.19/Myreview.pdf -m "<commit message>"`
* Run `git push`

Note that you can use the repository to keep track of your files. In other words, you do not have to use the repository for final submission versions only. You can create an initial version of your file when you start working on it and keep updating it till the deadline (whenever you finish a coherent set of changes, make sure to commit and push).
