Client Requirement
------------------
Whoever clone’s the repo, just by running a single command should be able to get the rating of the specified movie from http://www.omdbapi.com/

Prerequisite:
-------------
1.Required Linux Operating system

2.Docker should be installed on the Operating system

3.Required API Key for to access the omdbapi Database

Procedure to execute the command
---------------------------------
Step1:Clone the Repo from the https://github.com/Palanimks/Client_Task.git

Step2:execute the ./script.sh file 

Step3:Enter the Movie name 

Output
------
Once we enter the movie name in the execute command,Now we will  get the movie Tittle and Rotten Tomato rating

How it works
------------
Step1:once execute the ./script.sh file it wil create the docker image.

Step2:By using COPY module, will copy the ./find.sh to container from the local directory.

Step3:now container will create and will execute the ./find.sh script

Author
------
Palanivel M
