# lab4
Bootcamp nivelPRO - Laboratory 4

$ git flow init
$ git flow feature start add-file-1
$ vim README-3.txt
$ git add README-3.txt
$ git commit . -m "Add README-3.txt"
$ git remote add origin https://github.com/dicodiaz/lab4.git
$ git push -u origin master
$ git push -u origin develop
$ git push -u origin feature/add-file-1
$ git flow feature finish add-file-1
$ git push -u origin develop
$ git flow release start v.0.1.0
$ git flow release finish v.0.1.0
$ git flow feature start add-file-2
$ vim README-4.txt
$ git add README-4.txt
$ git commit . -m "Add README-4.txt"
$ git push -u origin feature/add-file-2
$ git flow feature finish add-file-2
$ git flow release start v.0.2.0
$ git flow release finish v.0.2.0
$ git flow hotfix start v.0.2.1
$ git flow hotfix finish v.0.2.1
$ git push -u origin develop
$ git push -u origin master
