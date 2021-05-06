#  Cannot clone or checkout repository: //github.com/b
#  Spring Config Server - No such label: master
#  git: not found
#  Error occured cloning to base directory.
#  Invalid remote: origin



I have added 

    1. application.yml file --> used in git 
    
    2. application.properties file used in local project
    
    2. main java class
    
    3. pom.xml
    
    4. Use "admin" as username and password while hitting the end point in any browser
        http://localhost:8888/login
    
    5. The hit http://localhost:8888/application/main
        Now you can able to read configuration file from remote server -->git.
        
        NOTE: Insted of "default" we have to use "main" in latest versions.
