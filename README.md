# HWDocker

# Add Docker file

1.Add the Docker file and docker ignore file to the Project hierarchy

2.Amend the entry point in Docker file [“.net”,”{projectname.dll}”]

# Build Project & Run Docker Image:

1.Navigate to the Project folder in terminal(mac) and run the command

      # docker build –t (dockerImageName) -> creates a docker image
   
2.Run the below command to run the app at port no 80
      # docker run -d -p 80:80 (dockerImageName)

# Save the Docker Image

1.Run the command to save the docker image

    # docker save (dockerImageName) > (dockerOutputName).tar

# Get the Docker Image from .tar file

     # 1.docker load –i (dockerOutputName).tar

     # 2.docker run –d –p (portnumber):80 (dockerImageName). 

# Make the machine or server running this docker listens to this port (80)

Execution:

    DockerImage : https://s3.us-east-2.amazonaws.com/weatherappamith/weatherappamith.tar

    README: https://github.uc.edu/dubbasar/HWDocker/blob/master/README.md

    Mac terminal : docker run -d -p 80:80 weatherappamith











 
