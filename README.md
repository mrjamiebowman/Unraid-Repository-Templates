# Unraid Docker Repository Templates
A collection of useful developer containers for Unraid.   

# UNDER CONSTRUCTION (12/16/21)
Work In Progress.. hoping to get this done ASAP

## Containers Included
* Azure Build Agent (.NET 6, Terraform, Ansible, Packer)  
* NuGet Server
* Parrot OS
* Kafka
* Microservice Toolbox (MBOX)

## Unraid Useage

Firstly you need to be running unRAID ver 6.0.0 or later, once installed follow the instructions below:-

1. Navigate to "Docker" tab and then the "Docker Repositories" sub-tab in the unRAID webui
2. Enter in a URL of `https://github.com/mrjamiebowman/docker-templates` in the "Template repositories" field
3. Click on the "Save" button
4. Click back to "Docker" tab and then click on the "Add Container" button
5. Click on the "Template" dropdown menu and select the desired Docker image
6. Click the "Advanced View" toggle on the top right and fill in required fields e.g. volume data, environment variables etc
7. Click on the "Create" button at the bottom of the window to begin pulling down the Docker image
8. Once the image is downloaded you should see it appear in the "Docker Containers" sub-tab