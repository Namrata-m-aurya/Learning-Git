First of all 
####
I will make changes in the local and merge those changes in my remote repo. 

the commands which i will use is.

first add the files(in short the changes in local ) to staged changes and then commit with message. 

namrata@it002078:~/git/Learning-Git$ git add Getting Started.md 
fatal: pathspec 'Getting' did not match any files
namrata@it002078:~/git/Learning-Git$ git add Getting\ Started.md 
namrata@it002078:~/git/Learning-Git$ git commit -m "Getting started."
[main 5ace448] Getting started.
 1 file changed, 9 insertions(+)
 create mode 100644 Getting Started.md
namrata@it002078:~/git/Learning-Git$
####
git fetch *****
downloads new data from the remote and it does not integrate the new data in our files it has harmless nature. 

git pull *******
it downloads the new data to our local from the remote and integrates the data also there can be merge conflicts which can either be resolved automatically or manually. 

After this i tried to pull and i was able to pull . (point to be noted it could be done fast forwarded. )

git restore filename *****
will discard the changes in the file. 



