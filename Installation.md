# Simple-Devops-Project(For this project we are implementing everythin on Ubuntu 18.04) 
In order to install most of the devops tools Java is a dependancy
1.  Install Java on Ubuntu:
    . sudo apt update
    . sudo apt install openjdk-8-jdk
    . java -version - To verify installed Java version
  
2.  Install Jenkins on Ubuntu:
    . wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -
    . sudo sh -c 'echo deb https://pkg.jenkins.io/debian-stable binary/ > \
      /etc/apt/sources.list.d/jenkins.list'
    . sudo apt-get update
    . sudo apt-get install jenkins
3.  Install Maven on Ubuntu:
    . sudo apt install maven
    . mvn -version - To verify installed version of Maven
4.  Install & Configure Ansible on Ubuntu:
    . sudo apt update
    . sudo apt install software-properties-common
    . sudo apt-add-repository --yes --update ppa:ansible/ansible
    . sudo apt install ansible
    . sudo useradd ansibleadmin
    . sudo usermod -aG sudo ansibleadmin
    
