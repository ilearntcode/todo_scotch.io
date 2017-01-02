# todo_scotch.io

When you start working on a project, you can initialize your project in two ways. 

1. Initializing a new repository in an existing directory

> $ git init

2. Clone an existing repository
You can get a copy of an existing git repository 
> $ git clone PATH/TO/REPO/PROJECT_NAME

If you want to clone it into a different directory named something other than PROJECT_NAME, you can specify that as the next command line option:
> $ git clone PATH/TO/REPO/PROJECT_NAME NEW_DIRECTORY_NAME


You can not clone an existing repository into a directory that isn't empty. To do that you can use either of the command below:

> git init
> git remote add origin PATH/TO/REPO
> git fetch
> git checkout -t origin/master

> 
* git init
* git remote add origin PATH/TO/REPO
* git pull origin master
>