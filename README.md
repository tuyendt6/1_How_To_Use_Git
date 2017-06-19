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
  - git feth branch_name ( change current branch in local , notice the name path)
  - git commit -m "first commit"
  - git push origin master:branch_name ( push code to branch_name ) .

