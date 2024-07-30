# MODULE TITLE
This repository houses the devcontainer and docker image for the MODULE module at the University of Lincoln.
## What is Docker?
Docker is a platform which allows developers to create and share containers.

A container is an environment separate from your main operating system, which includes all of the requirements to run a piece of software. You can think of it like a box which you can take anywhere,
and when opened, the software inside works exactly the same way, no matter where you are running it.

This helps us technicians to give every module the exact coding environment it needs, without causing any conflicts.

If you would like to learn more about how Docker works in your labs, please feel free to contact us at technician@lincoln.ac.uk.

## How do I use the Docker container for this module at home?

We strongly recommend using the Docker container for your modules on your personal devices, as it recreates the exact coding environment you use in the labs without installing lots of stuff on your computer which may conflict with the required software for other modules you are studying.

### Prerequisites

These prerequisites are the same for every Computer Science module using Docker containers, so you should only need to do this once and it will work for the rest of your degree.

1. Download and install Docker Desktop: https://www.docker.com/products/docker-desktop/

2. Download and install VSCode: https://code.visualstudio.com/

3. Install the Remote Development extension for VSCode: https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack

### Process

1. Clone this repository to your computer by clicking the green 'Code' button, and clicking 'Download ZIP'.
2. Extract the downloaded Zip file.
3. Inside the extracted folder is a folder entitled 'MODULE FOLDER' which contains the .devcontainer folder. Move 'MODULE FOLDER' to wherever you like, this will be your working directory for this module.
4. Make sure Docker Desktop is running. You can minimise the window.
5. Open VS Code, go to File -> Open Folder, and select your 'MODULE FOLDER' folder.
6. Click the 'Reopen in container' pop up in the bottom right corner of your VS Code window. If you do not see this pop up, press F1, and type 'Reopen in Container', and click on the 'Dev Containers: Reopen in Container' command.
7. The Docker image will now be downloaded, and the container will be started. You can click 'show log' in the bottom right corner to see what is going on.
8. Your docker container is now running! Within this VS Code window, you can now run workshop or assignment material exactly the same as in the computing labs.
9. If we ever push an update to the container, you will need to go to Docker Desktop -> Images, find ghcr.io/socstech/MODULE, click the ... button, and click pull. This will pull the most recent version of the docker container. There should be Blackboard announcements letting you know if you ever need to do this, but it is good to do this step every time before you want to use the container.

### Troubleshooting

If you are struggling to get this to work, try these common troubleshooting steps:

1. Restart your computer. Always a good start.
2. Make sure Docker Desktop is open and running.
3. Make sure Docker Desktop is updated.
4. Make sure VS Code has the Remote Development extension pack. You can install this through the Extensions tab in VS Code if it isn't working through the web link above.
