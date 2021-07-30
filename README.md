# devops-technical-task

* Build a Springboot application using gradlewrapper
* Create a Dockerfile based on Openjdk and add Springboot application jar file. Make Docker container to execute jar file during startup
* Create a docker-compose file which will bring up Mysql container and Springboot container
* Add user to the database (curl localhost:8080/demo/add -d name=First -d email=someemail@someemailprovider.com)
* Check user was added to databse (curl localhost:8080/demo/all)