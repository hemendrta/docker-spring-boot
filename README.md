# docker-spring-boot <br>
#containering an app and running using docker

#Steps
<ul>
<h5><li>Create a file by the name Dockerfile in the project</li></h5>
<h5><li>Add the details which are "FROM" -- from which the image needs to be created, "ADD" -- location of the jar file that is the target directory, "EXPOSE" -- port number which you want the application to run, and "ENTRYPOINT" -- initial commands which would run the app.</li></h5>
<h5><li>Build the docker image for the project prior to this build the jar file for the project, use command "docker build -f Dockerfile -t tagName" for creating the image</li></h5>
<h5><li>Use command "docker run -p ExposedPort:ContainerPort imageName" to run the image in the container</li></h5>
</ul>
