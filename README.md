# ProjectX

As you will see, I ran into some problems while working on this assignment. Problems I simply wasn't able to solve. I went to great lengths attempting to problem solve this as I spent hours reading on forums and support channels. But, nothing seem to have helped.

So... as I had no other option, the only way to proceed with the assignment was to first create the repo on GitHub, clone it and then push content to it. I hope that is ok.


## Error message

This is the message I kept getting every time I tried to create a remote repo and I just can't understand what I am doing wrong.
```
no such identity: /home/sonny/.ssh/id_rsa: No such file or directory
git@github.com: Permission denied (publickey).
fatal: Could not read from remote repository.

Please make sure you have the correct access rights
and the repository exists.
```

## Terminal history

Here is the complete terminal history. I spent hours and hourse trying to sort out this issue but I simply couldn't.
I'm not sure what's wrong.
```
449  mkdir ProjectX
  450  ls
  451  cd ProjectX/
  452  mkdir docs src data
  453  ls
  454  cd docs
  455  ls
  456  mkdir reports imgs
  457  cd ..
  458  ls
  459  cd src
  460  mkdir html css js
  461  cd ..
  462  cd data
  463  ls
  464  touch data.txt
  465  echo "Hello Data" >> data.txt
  466  cat data.txt
  467  cd ..
  468  ls
  469  cd docs
  470  ls
  471  cd reports
  472  touch report_one.txt report_two.txt
  473  ls
  474  cd ..
  475  ls
  476  cd ..
  477  ls
  478  cd src
  479  ls
  480  cd css
  481  touch style.css
  482  cd ..
  483  cd html
  484  touch index.html
  485  cd ..
  486  cd js
  487  touch script.js
  488  cd ..
  489  ls
  490  cd ..
  491  ls
  492  cd ..
  493  ls
  494  echo history
  495  history
  496  ls
  497  cd ProjectX/
  498  git init
  499  git add .
  500  git status
  501  git commit -m "Folder and file structure created and initiated"
  502  git config --global init.defaultBranch main
  503  git branch -m mian#
  504  git branch -m main
  505  git status
  506  ls
  507  cd docs
  508  ls
  509  cd imgs
  510  touch .gitkeep
  511  git status
  512  git add .
  513  git status
  514  git commit -m "Added .gitkeep to the imgs folder"
  515  git add remote https://github.com/sonnystark/ProjectX
  516  cd ..
  517  ls
  518  cd ..
  519  ls
  520  git add remote https://github.com/sonnystark/ProjectX
  521  git push+
  522  git push
  523  git remote add ProjectX https://github.com/sonnystark/ProjectX
  524  git push ProjectX
  525  git push --set-upstream ProjectX main
  526  git remote -v
  527  git remote show ProjectX
  528  git push --set-upstream ProjectX main
  529  git push
  530  git push --set-upstream ProjectX main
  531  git remote update
  532  git push
  533  git remote add ProjectX https://github.com/sonnystark/ProjectX.git
  534  git add remote https://github.com/sonnystark/ProjectX.git
  535  git push
  536  git add remote https://github.com/sonnystark/ProjectX.git
  537  git remote add ProjectX git@github.com:sonnystark/ProjectX.git
  538  git push --set-upstream git@github.com:sonnystark/ProjectX.git main
  539  git pull
  540  git push --force-with-lease --set-upstream git@github.com:sonnystark/ProjectX.git main
  541  git add remote https://github.com/sonnystark/ProjectX.git
  542  git remote add ProjectX git@github.com:sonnystark/ProjectX.git
  543  git push
  544  git push --set-upstream ProjectX main
  545  git diff --staged
  546  git status
  547  git push --set-upstream ProjectX main
  548  git push -u origin main
  549  git push -u ProjectX main
  550  git push ProjectX main
  551  git fetch
  552  git push
  553  git config --global user.name "sonnystark"
  554  git config --global user.email "sonny.stark@posteo.net"
  555  git config --global color.ui auto
  556  git push
  557  git push --set-upstream ProjectX main
  558  git push git@github.com:sonnystark/ProjectX.git
  559  git pull
  560  git pull git@github.com/sonnystark/ProjectX.git
  561  git status
  562  git branch
  563  git push --set-upstream ProjectX main
  564  git checkout main
  565  git commit -m "Folder and file structure created and initiated"
  566  ls
  567  touch README.md
  568  git remote add origin https://github.com/sonnystark/ProjectX.git
  569  git push --set-upstream origin main
  570  git remote add origin git@github.com/sonnystark/ProjectX.git
  571  git remote --v
  572  ls
  573  ls -a
  574  rm .git
  575  rmdir .git
  576  rmdir -r .git
  577  rm -r .git
  578  y
  579  ls
  580  ls -a
  581  clear
  582  pwd
  583  ls
  584  cd ..
  585  ls
  586  rm -r ProjectX/
  587  ls
  588  pwd
  589  sudo dnf upgrade
  590  pwd
  591  mkdir ProjectX
  592  cd ProjectX/
  593  pwd
  594  mkdir docs src data
  595  cd docs
  596  mkdir reports imgs
  597  cd reports
  598  touch report_one.txt report_two.txt
  599  cd /ProjectX
  600  cd ..
  601  pwd
  602  cd ..
  603  cd src
  604  mkdir html css js
  605  cd js
  606  touch script.js
  607  cd ..
  608  cd html
  609  touch index.html
  610  cd ..
  611  cd css
  612  touch style.css
  613  ls
  614  cd ..
  615  ls
  616  ls -a
  617  cd ..
  618  cd data
  619  touch data.txt
  620  echo "Hello Data" >> data.txt
  621  cd ..
  622  pwd
  623  ls
  624  git init
  625  git branch
  626  git status
  627  git add .
  628  git status
  629  git commit -m "Initial setup"
  630  git remote add ProjectX git@github.com:sonnystark/ProjectX.git
  631  git push ProjectX main
  632  git status
  633  git remote add ProjectX https://github.com/sonnystark/ProjectX.git
  634  git push ProjectX main
  635  git push ProjectX master
  636  git push ProjectX main
  637  git remote -v
  638  ssh -T git@github
  639  ssh -T git@github.com
  640  cd ..
  641  pwd
  642  mkdir .ssh
  643  cd .ssh
  644  ls -a
  645  cd ..
  646  ls
  647  ls -a
  648  cd .ssh
  649  ls -a
  650  touch config
  651  ls -a
  652  ssh-keygen -t ed25519 -C "sonny.stark@posteo.net"
  653  $ eval "$(ssh-agent -s)"
  654  > Agent pid 59566
  655  eval "$(ssh-agent -s)"
  656  > Agent pid 59566
  657  eval "$(ssh-agent -s)"
  658  Agent pid 59566
  659  eval "$(ssh-agent -s)"
  660  > Agent pid 59566
  661  '$(ssh-agent -s)' '>' Agent pid 59566
  662  '>' Agent pid 59566
  663  ssh-add ~/.ssh/id_ed25519
  664  ssh-keygen -t ed25519-sk -C "sonny.stark@posteo.net"
  665  pwd
  666  cd ..
  667  pwd
  668  cat ~/.ssh/id_ed25519.pub
  669  ssh -T git@github.com
  670  sudo ssh -T git@github.com
  671  pwd
  672  ls -a
  673  cd .ssh
  674  ls
  675  cat config
  676  nano config
  677  ls
  678  cd ..
  679  ls -a
  680  cat .bash_profile
  681  nano .bash_profile
  682  pwd
  683  ls -a
  684  nano .bashrc
  685  pwd
  686  ls
  687  cd CodeLabsAcademy/
  688  ls
  689  cd ProjectX/
  690  git status
  691  git remote -v
  692  git push ProjectX main
  693  sudo git push ProjectX main
  694  git remote update
  695  cd ..
  696  pwd
  697  ls -a
  698  cd .ssh
  699  ls -a
  700  nano config
  701  cd CodeLabsAcademy/
  702  ls
  703  cd ..
  704  cd C
  705  cd ..
  706  cd CodeLabsAcademy/
  707  pwd
  708  ls
  709  cd sonny
  710  ls
  711  cd CodeLabsAcademy/
  712  ls
  713  cd ProjectX/
  714  git push ProjectX main
  715  ls
  716  cd ..
  717  ls
  718  rm -r ProjectX/
  719  ls
  720  mkdir ProjectX
  721  cd ProjectX/
  722  mkdir docs src data
  723  cd docs
  724  mkdir reports imgs
  725  cd reports
  726  touch report_one.txt report_two.txt
  727  cd ..
  728  ls
  729  cd imgs
  730  touch .gitkeep
  731  cd ..
  732  ls
  733  cd src
  734  mkdir html css js
  735  cd css
  736  touch style.css
  737  cd ..
  738  cd js
  739  touch script.js
  740  cd ..
  741  cd html
  742  touch index.html
  743  cd ..
  744  ls
  745  cd data
  746  touch data.txt
  747  echo "Hello Data" >> data.txt
  748  echo "# ProjectX" >> README.md
  749  git init
  750  git add README.md
  751  git commit -m "first commit"
  752  git branch -M main
  753  git remote add origin git@github.com:sonnystark/ProjectX.git
  754  git push -u origin main
  755  git remote add origin git@github.com:sonnystark/ProjectX.git
  756  git branch -M main
  757  git push -u origin main
  758  history
```
