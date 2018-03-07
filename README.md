# cookbook
hobby project to learn new technologies, practices

Overview: 
  The goal of this project is develop a cookbook app that is accessible by web, mobile, and service clients. 

Technologies: 
* Java
* Spring
* SpringFox  // swagger ui generation
* NodeJs
* Mondgo DB
* AngularJS
* Rest
* Git
* 
 
Architecture: 

[UI Client] --> Browser(angularJs) 
					|
						--> [JSON/HTTP:80]---> Container (TBD) ---> uSdS(mongoDb)
					|
			[api Consumer]

Planned Features: 
* View,Create and Manage Recipes
* Share Recipes:  email, web urls
* Collaborate on recipes:  add comments, create recipe variants
* Rank/Rate recipes
