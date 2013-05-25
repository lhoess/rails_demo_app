Rails Dev Notes


Start at project folder (root)
run: 
$ rail new <project_name> (creates new folder under root)
move into <project_name> (cd <project_name>)
modify .gemfile

run: 
$ bundle update
$ bundle insall --without production (to keep out production settings in the .gemfile)

$ git init
$ git add . (add all the files from <project_name>)
$ git commit -m "initial commit"

create: github repo 
$ git remote add origin git@github.com:<username>/demo_app.git
$ git push -u origin master



DATABASE
$ rails generate scaffold User name:string email:string (create User model with columns name, email)
bundle exec rake db:migrate (migrates DB to SQLite or ???)



RAILS SERVER 
$ rails s (from within <project_name>, starts server on port 3000)

