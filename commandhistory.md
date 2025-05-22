ubuntu@ip-172-31-3-203:~$ history
    1  sudo apt update
    2  sudo apt install openjdk-17-jre
    3  java -version
    4  curl -fsSL https://pkg.jenkins.io/debian/jenkins.io-2023.key | sudo tee   /usr/share/keyrings/jenkins-keyring.asc > /dev/null
    5  echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc]   https://pkg.jenkins.io/debian binary/ | sudo tee   /etc/apt/sources.list.d/jenkins.list > /dev/null
    6  sudo apt-get update
    7  sudo apt-get install jenkins
    8  sudo cat /var/lib/jenkins/secrets/initialAdminPassword
    9  vi s3upload.sh
   10  vim s3upload.sh
   11  chmod 777 s3upload.sh
   12  ./s3upload.sh
   13  curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
   14  unzip awscliv2.zip
   15  sudo ./aws/install
   16  sudo apt update
   17  sudo apt install unzip -y
   18  unzip awscliv2.zip
   19  sudo ./aws/install
   20  aws --version
   21  aws configure
   22  vim s3upload.sh
   23  ./s3upload.sh
   24  history
ubuntu@ip-172-31-3-203:~$ 
