# TestGitRemoteAndLocal
Testing git between remote and local 

Commands for all 
 4  git status
    5  git log --oneline
    6  history 10
    7  history 50
    8  nano README.md
    9  git add README.md
   10  git commit -m "updated commands of today"
   11  git push origin master
   12  git pull origin master
   13  git pull origin origin/master
   14  cd gitDemoForCTTraining/
   15  cd ..
   16  git branch --list
   17  git branch newbranchFromMaster
   18  git branch --list
   19  git checkout newbranchFromMaster
   20  ls
   21  git branch --list
   22  git checkout master
   23  git checkout newbranchFromMaster
   24  echo "test from new branch" >> newbranch.txt
   25  git add newbranch.txt
   26  ls
   27  echo "new branch abc" >> file.abc
   28  ls
   29  git add file.abc
   30  git commit -m "commit from new branch"
   31  git status
   32  git checkout master
   33  git status
   34  ls
   35  git checkout newbranchFromMaster
   36  checkout branch master
   37  git checkout master
   38  git log --oneline
   39  git branch
   40  ls
   41  git checkout newbranchFromMaster
   42  git log --oneline
   43  git checkout master
   44  git checkout newbranchFromMaster
   45  notepad README.md
   46  git status
   47  git commit -a -m "updated readme.md in new branchfrommaster"
   48  git status
   49  git log --oneline
   50  git log --oneline
   51  git checkout master
   52  git log --oneline
   53  git merge newbranchFromMaster
   54  git log --oneline
   55  ls
   56  git log --oneline
   57  git checkout newbranchFromMaster
   58  git log --oneline
   59  git status
   60  git pull origin master
   61  git checkout master
   62  git pull origin master
   63  git push origin master
   64  git pull origin master
   65  history
   66  history 100
   67  notepad README.md
   68  git commit -a -m "updated readme.md in new master"
   69  git push origin master
   70  git pull origin master
   71  git log --oneline
   72  git checkout newbranchFromMaster
   73  git log --oneline
   74  git checkout master
   75  q
   76  ls
   77  cd gitDemoForCTTraining/
   78  git log --oneline
   79  cd ..
   80  git checkout -b featurebranch
   81  git log --oneline
   82  gti branch
   83  git branch
   84  git branch -a
   85  git branch -av
   86  ls
   87  git log --online --decorate
   88  git log --oneline --decorate --graph
   89  git log --oneline --decorate --graph
   90  git log --oneline --decorate --graph -all
   91  git log --oneline --decorate --graph --all
   92  ls
   93  notepad file.abc
   94  git commit -am "modified fiel.abc"
   95  git status
   96  git log --oneline --decorate --graph
   97  git checkout master
   98  git log --oneline --decorate --graph
   99  notepad test.abcd
  100  git commit -am "added test.abd into master"
  101  git add test.abcd
  102  git commit -am "added test.abd into master"
  103  git merge featurebranch
  104  git log --oneline --decorate --graph
  105  git status
  106  git log --oneline --decorate --graph
  107  git checkout featurebranch
  108  git log --oneline --decorate --graph
  109  git checkout master
  110  git log --oneline --decorate --graph --all
  111  git checkout featurebranch
  112  git log --oneline --decorate --graph --all
  113  git checkout master
  114  git branch -d featurebranch
  115  git branch
  116  git log --oneline --decorate --graph --all
  117  git log --oneline --decorate --graph
  118  git log --oneline --decorate --graph --all
  119  git checkout -b large-feature
  120  ls
  121  notepad file.abc
  122  notepad file.abc
  123  git commit -am "file.abc updated with 3 changes"
  124  notepad file1
  125  git commit -am "file1 updated with 2 changes"
  126  git status
  127  git checkout master
  128  notepad file.abc
  129  git commit -am "file.abc update on master branch"
  130  echo "new file created" >> file.nm
  131  git add .
  132  git commit -am "file.nm is created"
  133  git status
  134  git log --oneline --decorate --graph --all
  135  git merge large-feature
  136  git merge abort
  137  git merge --abort
  138  cd gitDemoForCTTraining/
  139  git status
  140  git log --oneline
  141  git checkout -b quick-feature
  142  git log --oneline
  143  ls
  144  echo "test 1 " >> test.abc
  145  git add test.abc
  146  git commit -am "new file added test.abc"
  147  git push
  148  git log --oneline
  149  ls
  150  mkdir DemoProjectMergeRebase
  151  cd DemoProjectMergeRebase/
  152  git init
  153  gti status
  154  git status
  155  git clone https://github.com/ravikp92/starter-web.git
  156  clear
  157  git log
  158  ls
  159  echo "file 1" >> file1.txt
  160  echo "file 1" >> filer1.abc
  161  ad filer1.abc
  162  git add filer1.abc
  163  git commit -a -m "filer1 addded"
  164  git add filer2.abc
  165  echo "file 2" >> filer2.abc
  166  git add filer2.abc
  167  git commit -a -m "filer2 addded"
  168  git checkout -b fixes
  169  git log
  170  git merge-base fixes master
  171  echo "a1 fixes" >> filer3.abc
  172  git add .
  173  git add filer3.abc
  174  git commit -a -m "filer3 addded on fixes branch"
  175  echo "a2 fixes " >> filer4.abc
  176  git add filer4.abc
  177  echo "modified filer4abc" >> filer4.abc
  178  git commit -a -m "filer4 modified on fixes branch"
  179  git log
  180  q
  181  git status
  182  git checkout master
  183  echo "filer5 on master" >> filer5.abc
  184  git add filer5.abc
  185  git commit -a -m "filer5 on master branch"
  186  echo "modified filer5 on master" >> filer5.abc
  187  git commit -a -m "filer5 on master branch"
  188  ls
  189  git checkout fixes
  190  git checkout -fixeschild
  191  git checkout -b fixeschild
  192  git checkout fixes
  193  git checkout master
  194  git log
  195  git checkout fixes
  196  git log
  197  history
  198  clear
  199  git log
  200  git rebase master
  201  git log
  202  git log --decorate --graph
  203  git log --oneline --decorate --graph
  204  ls
  205  git checkout master
  206  git merge fixes
  207  git log --oneline --decorate --graph
  208  git status
  209  git checkout fixes
  210  git status
  211  ls
  212  git checkout master
  213  ls
  214  ls
  215  echo "file 3 updated on master" >> file3.abc
  216  git commit -am "fiel 3 updated on master branch"
  217  echo "file 1 updated on master" >> filer1.abc
  218  git add file3.abc
  219  git commit -am "filer1 updated on master branch"
  220  git status
  221  git log --onleine
  222  git log --oneilne
  223  git log --oneline
  224  git checkout master
  225  git checkout fixes
  226  ls
  227  echo "filer1 - fixes" >> filer.abc
  228  git commit -am "filer1 updated on fixes branch"
  229  echo "filer1 - fixes" >> filer1.abc
  230  git commit -am "filer1 updated on fixes branch"
  231  git status
  232  git log --oneline
  233  echo "filer1 - fixes again" >> filer1.abc
  234  git commit -am "filer1 updated again on fixes branch"
  235  git log --oneline
  236  git rebase master
  237  git status
  238  git rebase --abort
  239  git status
  240  git log --oneline
  241  git rebase master
  242  notepad filer1.abc
  243  git status
  244  git commit -a -m "Filer1 abc merged with changes"
  245  git log --oneline
  246  git status
  247  git rebase --continue
  248  git status
  249  git add filer1.abc
  250  git status
  251  git commit -a -m "Filer1 abc merged with changes again"
  252  git rebase --continue
  253  git status
  254  git log --oneline
  255  cat filer.abc
  256  cat filer1.abc
  257  notepad filer1.abc
  258  git log --oneline
  259  git checkout master
  260  git log --oneline
  261  cat filer1.abc
  262  git merge fixes
  263  git log --oneline
  264  git log 8aacb51
  265  git log -n 1
  266  git log --stat -n 1
  267  git log --oneline
  268  git log --stat 8aacb51
  269  git checkout 8aacb51
  270  ls
  271  cat filer2.abc
  272  git checkout -b securityfeature
  273  git log --oneline
  274  ls
  275  echo "file 6" >> filer5.abc
  276  git add -filer5.abc
  277  git add filer5.abc
  278  git commit -m "filer5 created at security feature from one commit of master"
  279  git log --oneline
  280  git checkout master
  281  git log --oneline
  282  git checkout securityfeature
  283  git merge
  284  git log --oneline
  285  git checkout master
  286  git merge 8aacb51
  287  ls
  288  git log --oneline
  289  git history
  290  history
  291  ls
  292  cd ..
  293  cd test/TestGitRemoteAndLocal/
  294  git status
  295  git push
  296  ls
  297  git log --oneline
  298  git cherry-pick 41fff8a filer1.abc
  299  git remote
  300  mkdir testproject
  301  cd testproject/
  302  git clone https://github.com/ravikp92/gitDemoForCTTraining.git
  303  git branch -a
  304  git remote show origin
  305  git remote show
  306  git remote add origin https://github.com/ravikp92/gitDemoForCTTraining.git
  307  git remote show origin
  308  git fetch
  309  git branch -a
  310  git remote show origin
  311  git fetch
  312  git remote show origin
  313  git remote show origin
  314  git log
  315  git log --oneline
  316  git log --oneline
  317  git branch -a
  318  git merge origin/master
  319  git merge origin/main
  320  git merge
  321  git pull
  322  git merge
  323  git fetch
  324  git merge origin/main
  325  git merge origin/main
  326  git merge origin/master
  327  git pull origin master
  328  cd..
  329  cd ..
  330  cd ..
  331  mkdir test
  332  cd test
  333  git remote add origin
  334  git remote add origin https://github.com/ravikp92/TestGitRemoteAndLocal.git
  335  git branch -a
  336  ls
  337  git remote show origin
  338  git fetch
  339  ls
  340  git merge origin/main
  341  git status
  342  git log --oneline
  343  git pull origin
  344  git pull origin main
  345  git pull origin master
  346  git remote -v
  347  git status
  348  git pull origin master
  349  git pull origin main
  350  git log --oneline
  351  gti clone https://github.com/ravikp92/TestGitRemoteAndLocal.git
  352  git clone https://github.com/ravikp92/TestGitRemoteAndLocal.git
  353  ls
  354  cd TestGitRemoteAndLocal/
  355  ls
  356  cat README.md
  357  git log --oneline
  358  echo "index.html created at local" >> index.html
  359  git add index.html
  360  git commit -a -m "index.html created at local"
  361  git status
  362  git push
  363  git checkout -b newbranchfromlocal
  364  git status
  365  echo "file added at local newbranchfromlocal" >> file.txt
  366  git add file.txt
  367  git commit -a -m "file added at local newbranchfromlocal"
  368  git push
  369  git checkout master
  370  git checkout main
  371  git merge newbranchfromlocal
  372  git status
  373  git log --oneline
  374  git push
  375  git branch -a
  376  git checkout newbranchfromlocal
  377  git push
  378  git push -u origin newbranchfromlocal
  379  git checkout main
  380  git branch -a
  381  git checkout newranchfromlocal
  382  git checkout newbranchfromlocal
  383  git pull
  384  ls
  385  git checkout master
  386  git checkout main
  387  git merge newbranchfromlocal
  388  git status
  389  git log --oneline
  390  git push
  391  git log --oneline
  392  history 50
  393  notepad README.md
  394  git status
  395  git commit -am "Read me added with commands exectuted"
  396  git push
  397  ls
  398  cat file.txt
  399  notepad file.txt
  400  git status
  401  git pull origin/main
  402  git pull origin
  403  notepad file.txt
  404  git pull origin
  405  notepad file.txt
  406  git pull origin
  407  git status
  408  'git commit -am "file txt has been updated locally"
  409  git commit -am "file txt has been updated locally"
  410  q
  411  git commit -am "file txt has been updated locally"
  412  git status
  413  git pull
  414  notepad file.txt
  415  git pull
  416  git merge
  417  git status
  418  git add file.txt
  419  git commit -a -m "merged file txt"
  420  git pull
  421  cat file.txt
  422  git push
  423  git log --oneline
  424  git checkout newbranchfromlocal
  425  git merge main
  426  git status
  427  git log --oneline
  428  git checkout master
  429  git checkout main
  430  git log --oneline
  431  git push
  432  git checkout newbranchfromlocal
  433  git push origin/newbranchfromlocal
  434  git push
  435  git checkout main
  436  git log --oneline --decorate --graph
  437  history 50
  438  git commit -am "commands updated for merge conflicts"
  439  ls
  440  git status
  441  LS
  442  ls
  443  git reset HEAD file.txt
  444  LS
  445  git status
  446  git log --oneline
  447  ls
  448  git reset HEAD file.txt
  449  git status
  450  git branch -a
  451  git checkout newbranchfromlocal
  452  notepad file.txt
  453  git status
  454  git add file.txt
  455  git status
  456  git restore --staged file.txt
  457  echo "new file added for stash" >> file2.txt
  458  git add file2.txt
  459  git status
  460  git stash
  461  git log --oneline
  462  git status
  463  git stash list
  464  echo "master file created after stash">> file3stash.txt
  465  git add file3stash.txt
  466  ls
  467  notepad README.md
  468  git status
  469  git stash
  470  git stash list
  471  git stash show stash@{0}
  472  git stash show stash@{1}
  473  git status
  474  notepad README.md
  475  git status
  476  git stash push -m "readme.md is updated when stash was not added"
  477  git stash list
  478  git checkout master
  479  git checkout main
  480  git status
  481  git log --oneline
  482  git checkout newbranchfromlocal
  483  git stash list
  484  git stash pop stash@{2}
  485  git stash list
  486  git stash apply stash@{1}
  487  git stash list
  488  git status
  489  git status
  490  git commit -am "push from stash .Updated files from stash to local branch"
  491  git log --oneline
  492  git status
  493  git stash list
  494  git stash drop stash@{1}
  495  git stash list
  496  git stash show
  497  git stash clear
  498  git stash list
  499  cat README.md
  500  ls
  501  git log --oneline
  502  git show 859e22e
  503  history

