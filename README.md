Raspberry Jenkins

This is my first attempt at creating a CI/CD pipeline on my Raspberry Pi 4. 

Jenkins Installation:

wget -q -O - https://jenkins-ci.org/debian/jenkins... | sudo apt-key add -

sudo sh -c 'echo deb http://pkg.jenkins-ci.org/debian binary/ > /etc/apt/sources.list.d/jenkins.list'

sudo apt-get update

sudo apt-get install jenkins -y

systemctl status jenkins.service

Locate default admin password
sudo cat /var/lib/jenkins/secrets/initialAdminPassword


