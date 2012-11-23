#Rails Girls Manila
##Installation Party at SourcePad Lounge
###23rd November 2012

Introduction by Co-organizer/Coach [Katherine Pe](http://twitter.com/katgironpe)
<br>
Demo by Coach [Bryan Bibat](http://twitter.com/bry_bibat)

## Installed the following...
  - SublimeText2
  - Rails using the Rails Installer on [railsinstaller.org](http://railsinstaller.org)
  - Git

## Created a sample Rails app called "testapp"...
  * Create new rails app

    $ rails new testapp</code>

  * Change directory (cd)

    $ cd testapp

  * Create basic functionality

    /testapp $ rails generate scaffold post title:string content:text

  * Prepare database

    /testapp $ rake db:create

  * Create database

    /testapp $ rake db:migrate

  * Check if Rails server is running

    /testapp $ rails server

    (To stop the server: Ctrl C)

## Learned about Git (version control system)...
  * Initialize git repository

    git init

  * Add all files to the repo
    git add .


  * Record the changes to the repo
    
    git commit -m "Initial commit"