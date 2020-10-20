# TestGitRemoteAndLocal
Testing git between remote and local 

Commands for all 
557  git clone https://github.com/ravikp92/TestGitRemoteAndLocal.git
  558  ls
  559  cd TestGitRemoteAndLocal/
  560  ls
  561  cat README.md
  562  git log --oneline
  563  echo "index.html created at local" >> index.html
  564  git add index.html
  565  git commit -a -m "index.html created at local"
  566  git status
  567  git push
  568  git checkout -b newbranchfromlocal
  569  git status
  570  echo "file added at local newbranchfromlocal" >> file.txt
  571  git add file.txt
  572  git commit -a -m "file added at local newbranchfromlocal"
  573  git push
  574  git checkout master
  575  git checkout main
  576  git merge newbranchfromlocal
  577  git status
  578  git log --oneline
  579  git push
  580  git branch -a
  581  git checkout newbranchfromlocal
  582  git push
  583  git push -u origin newbranchfromlocal
  584  git checkout main
  585  git branch -a
  586  git checkout newranchfromlocal
  587  git checkout newbranchfromlocal
  588  git pull
  589  ls
  590  git checkout master
  591  git checkout main
  592  git merge newbranchfromlocal
  593  git status
  594  git log --oneline
  595  git push
  596  git log --oneline
  597  history 50
