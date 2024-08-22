# setUpNewLaptop
First
SetUp nodejs
install https://nodejs.org/en/download/
install nvm-setup.exe from https://github.com/coreybutler/nvm-windows/releases
cd c:\
nvm install 16.13.0
nvm use 16.13.0
nvm list
cd c:\ 
npm install -g nodemon
that's it
you can test server>nodemon and client>npm start



\\\ IDE for edit commit on git

Solution:

Go to "Settings | Tools | Terminal" and click "Configure terminal keybindings".

Find "Plug-ins | Terminal | Switch Focus To Editor" action and change its keyboard shortcut (by default "Escape") via context menu.

Keybindings are IDE wide, so no need to change it for each project.

 git rebase -i HEAD~3 //number of commit have to change
 
 
 esc i 
 
 change pick to edit (for the commit you want to change)
 
 esc
 
 shift z
 
 git commit --amend   
 
 esc i 
 
 change commit
 
 esc
 
 shift z
 
 git rebase --continue
 
 git push -f (when rebase is done) 
  

 //normal git
git branch feature1 (create branch feature 1)
git log --all --graph (show all the history of commit)
git checkout feature1 (change to feature1 branch)

//when add new comment
git add .   (add all new thing)
git commit --m "big fixed" (big fix is the comment)

//merge git 
git checkout master
git merge feature1 -m "Merge feature 1" (change to master then merge feature1 to master, -m "Merge feature 1" is not necessary)

//when merge conflict
(correct code on ide)
git add .
git commit --m "Merge conflict resolved"

//when create a new git repository
git remote add origin http.... (the link of new git , origin mean github)
git checkout master
git push origin master
git checkout feature1
git push origin feature1  (feature1 branch also add to the new git repository)
git checkout master
git pull origin master (sync the master and origin master)

//delete branch
git branch -D feature1




//laravel
php artisan make:migration create_users_table
php artisan make:controller PostController









#for php vscode extension
Laravel Artisan

Laravel Blade Snippets

Laravel Blade Spacer

Laravel goto view

Laravel Snippets

Laravel Extra Intellisense

Live sass compiler ? (You might have this already)

Beautify css/sass/scss/less

https://getcomposer.org/download/

PHP Intellisense

Emmet Live
