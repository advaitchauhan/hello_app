# Ruby on Rails Tutorial: "hello, world!"

This is the first application for the
[*Ruby on Rails Tutorial*](http://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

Process of Creation
1) rails new (created default app)

2) pointed root of site (in routes.rb) to 'application#hello'

3) created hello method in application controller

4) 'commit'ted all changes to git, 'push'ed the version to github.
	git init     //initialize empty repository
	git add .    //add all files in current directory to repo
	git commit -a -m "Improve the README file"
	git commit -m "Initial commit"
	git remote add origin git@github.com:<username>/first app.git
	git push -u origin master

5) learned about branches and merges between them
	git checkout -b modify-README   //create new branch
	git branch                      //look at branches
	git checkout -f                 //checkout of git with previous version, delete new changes
	$ git checkout master           //Switched to branch 'master'
    $ git merge modify-README       //merge modify-README branch to master


6) created heroku and deployed to heroku!
	heroku create --stack cedar
	git push heroku master
	heroku open

	
