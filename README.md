# Information-Security-Project

# guidelines for all contributors

1- first of all u have to take a look to the issues section in order to have an idea about the issue which was assigned 
to u.

2- make sure that u r in master branch then pull and fetch the master branch 
     command lines -> git branch ( it gives u the branch which where u r )
                      git checkout master ( switch to the master branch ) 
                      git fetch
                      git pull   ( Update ur local master to move on)

3- then create a branch has the same name of the issue.
   make sure u r in the master branch (that's important, if u create a branch based on other branch instead 
   of the master branch, u would fuck us, mate ... be careful, please )
   then try this following command in order to create the new branch based on the master
      command lines -> git checkout -b  urusername/qbranchName    (exemple : med_dp/make_the_details_file)
                      
4.1- then work on the issue, do ur magic.
4.2- when u r working on the issue, make sure you do Commits frequently in order to explain what u r doing.
4.3- each commit shall contain the '#NumberIssue' ( take a look, each issue has an ID, exemple: 'the first commit #15')
4.3- also if u feel that the process is in progress, it would be better if u move it from the ToDo column to the In progress      column, so we know that all is fine with u.

5- after doing ur magic, push the branch to the repo, so we can test it and merge it to the master 
      command lines -> git push -u origin urname/branchName 
   then comment the name of the branch on the issue post      


TO DO LIST:

1- KEYBASE
2- PROJECT JEE
3- CONCEPTION (CLASS DIAGRAM)

     
     
THE SKELETON:

-frontend/
	-Vue.js front 
	views/
		Home.vue
		Vote.vue
		Co.vue
		De.vue
	index.html (<script src="dest/build.js" />)
	App.vue
	main.js
	routes.js
	dest/
		build.js // this file it will be build using a npm-run command don't worry 
	webpack.config.js // it's a config file generated by the vue command don't worry
-backend/
	Node.js REST API
	client/
		...
	app.js
	server.js
	routes/
		index.js
	db/
		connection.js

-we'll use the XMLHttpRequest ()  in order to send requests from the front-end to the REST API.
