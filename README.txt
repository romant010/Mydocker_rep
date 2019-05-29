# Mydocker_rep
$ cat /etc/os*release
$ sudo apt update
$sudo apt install apt-transport-https
$sudo apt install curl
$curl –fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add – the key linux
OK
$sudo add-apt-repository “deb [arch=amd64] https://download.docker.com/linux/ubuntu S(Lsb_release -cs) stable”  -  Download release version
$ sudo apt update
$sudo apt install docker-ce – install community version – Install ce docker version
$sudo systemctl status docker
$q – exit
$docker –v
$sudo usermode –aG docker SUSER – add user to group docker
$reboot Ubuntu
$docker run Hello-world
$docker images
Run image TomCut
$docker search tomcat
$docker pull tomcat   download image
$docker images
$docker ps running containers
$docker ps –a all containers running before
$docker run –it –p 1234:8080 tomcat    8080 the open port on tomcat but we connect from vm with port 1234
Open chrome my ip:1234
$cntrl+c
$docker ps
$docker ps –a
$Docker run –d –p 1235::8080  docker run on background d (demon) with port 1235
$docker ps
$Docker run –d –p 1236::8080  docker run on background d (demon) with port 1235
$docker search ngnix
$$Docker run –d –p 1237:80 nginx   docker run on background d (demon) with port 1235
Docker ps or ps –a
$docker rmi hello-world  cannot delete we before need delet container
$docker rm CONTAINER ID
$docker ps –a
$docker images
