1. create a new repository on the command line

  - git init
  - git add README.md
  - git commit -m "first commit"
  - git remote add origin https://github.com/tuyendt6/dsfdsfsdf.git
  - git push -u origin master

2. push an existing repository from the command line

  - git remote add origin https://github.com/tuyendt6/dsfdsfsdf.git
  - git push -u origin master
  

3. show all branch in local :

  - git branch -r .

4. push source code to other branch (not default branch )
  - git remote add branch_name https://github.com/tuyendt6/dsfdsfsdf.git ( add branch )
  - git fetch branch_name ( change current branch in local , notice the name path)
  - git commit -m "first commit"
  - git push origin master:branch_name ( push code to branch_name ) .

5. revert file in git :

   # Revert changes to modified files.
      git reset --hard
   # Remove all untracked files and directories. (`-f` is `force`, `-d` is `remove directories`)
      git clean -fd
 6. clone sub branch in git (not master branch )
    git clone -b mybranch --single-branch git://sub.domain.com/repo.git
