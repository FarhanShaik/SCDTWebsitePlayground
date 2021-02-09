# SCDTWebsitePlayground
Playing around with shit for the SCDT website

#start farhan.txt
-> opens file, notepad default for .txt files


start off: git clone
#clone a repository from online
--------------------------------------
to update from local to repo:
#git add files to update
-> git add farhan.txt
## git restore to clear staging

#git commit -m "MESSAGE"
#git push
-> updates online repo
-------------------------------------
to update from repo to local:
#git fetch
-> put most updated version of online repo in commit

#git status
-> look at what will be updated

#git merge
-> combines commit with local

----------------------------------------------
to revert to previous version:
#git log
-> look for correct version

#git checkout "hash" filename.txt
-> grabs version
#git commit
#git merge
-> updates local to match previous version
--------------------------------------------