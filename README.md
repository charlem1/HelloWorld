Charles Martins, Myona More, Hridaya Koirala, Brandon Mclarin

The goal of this task is to install the Docker software and use it to print out "Hello, Docker and Java!" This process is done using the IntelliJ software as well as the Docker software.
The user simply has to create a file in IntelliJ to print "Hello, Docker and Java!" Aftwards you have to build the Project by going to Build in the navigation bar and clicking Build Project. This will create a Main.class file.
Afterwards, the user will need to create a file named dockerfile. There are a number of commands the user will have to enter into the file. After, the user must open a terminal or command prompt, find the directory where both the Dockerfile and HelloWorld.class files are contained and build a docker image using a commmand in the terminal.
After the image is built the user can run it as a container. A container is a executable package that includes everything needed to run an app. This includes the code, runtime, tools, libraries and more. Finally when the user runs 'docker run hello-java', they should be able to see the same code they put in IntelliJ.
