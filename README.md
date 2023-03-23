##### test the project

    ./gradlew test 
    
##### build the project

    ./gradlew build

##### build Docker image called java-gradle; execute from root

    docker build -t java-gradle .
    
##### push image to repo 

    docker tag java-gradle java-gradle:latest
