
### Install Docker

  - #### Install Docker using the repository
  
     ##### Set up the repository
     
     ```bash
     sudo apt-get update
     sudo apt-get install \
        apt-transport-https \
        ca-certificates \
        curl \
        gnupg \
        lsb-release
     ```
     
     ##### Add Docker’s official GPG key:
     
     ```bash
     curl -fsSL https://download.docker.com/linux/debian/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
     ```
     ```bash
     echo "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/debian buster stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
     ```
     
     ##### Install Docker Engine
     
     ```bash
     sudo apt-get update
     sudo apt-get install docker-ce docker-ce-cli containerd.io
     ```
 - #### Install Docker using the repository
     
     ##### Download `.deb` Debian Docker Package
      https://download.docker.com/linux/debian/dists/buster/pool/stable/amd64/
     ##### Install `.deb` Debian Docker Package
      ```bash
      sudo dpkg -i /path/to/package.deb
      ```
 

