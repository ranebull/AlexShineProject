# AlexShineProject
## Virtual Laboratory of Information Security (VLIS)  
The project consists of 4 parts:
* [OWASP WebGoat](https://www.owasp.org/index.php/Category:OWASP_WebGoat_Project) 
* [OWASP Mutillidae 2](https://www.owasp.org/index.php/OWASP_Mutillidae_2_Project)
* [Damn Vulnerable Web Application (DVWA)](http://www.dvwa.co.uk)
* [OWASP Juice Shop](https://www.owasp.org/index.php/OWASP_Juice_Shop_Project)
# Install
```bash 
sudo apt-get update                        
sudo curl -fsSL htpps://get.docker.com | sh    
sudo apt-get -y install python-pip        
sudo pip install docker-compose      
git clone https://github.com/ranebull/AlexShineProject.git
cd AlexShineProject
sudo docker-compose up -d
```

# Manage the container
```bash
sudo docker stats        
sudo docker ps         
sudo docker-compose stop
sudo docker-compose up -d
sudo docker-compose up 
```
