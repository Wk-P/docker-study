# End Time : 2023/1/9 14:00
# Docker Study Note
***
##### Windows application - Virutal Box 
##### Linux OS - Ubuntu 22.04
##### Installed Docker Engine and Docker 
***
### # <u>Docker Install</u>  

**1.Install docker engine on ubuntu before installing docker and set up Docker's package repository.**
>tutorial docs:https://docs.docker.com/engine/install/ubuntu/#set-up-the-repository  

**2. Download docker destop DEG package and install docker desktop.**
>**tutorial docs**: https://docs.docker.com/desktop/install/ubuntu/
>**DEG package**: https://desktop.docker.com/linux/main/amd64/docker-desktop-4.15.0-amd64.deb?utm_source=docker&utm_medium=webreferral&utm_campaign=docs-driven-download-linux-amd64  

**3. Question Use KVM --> Dsiable !!!**
>`modprobe kvm` couldn't be run and run command `kvm-ok` to get the diagnostics
> 
> `INFO: Your CPU does not support KVM extensions`
> `KVM acceleration can not ne used`  

__Query__
1. I don't know wether docker will run successfully when the kvm funciton can't be used.
2. Why KVM function of CPU is unusable
***

## <u>Docker Commands</u>
**See a list of all images on this system.**  
>`docker images`  
    
**Fetch a container image to local.**
>`docker pull [container name]` 

__Run a Docker container based on this image.__
>`docker run [container name] [options] [arguments]`  

__Show all containers that are currently running.__
>`docker ps`  or `docker ps -a`

