  1  clear
    2  pwd
    3  sudo apt update && sudo apt -y upgrade
    4  reboot
    5  docker version
    6  curl -s https://api.github.com/repos/docker/compose/releases/latest   | grep browser_download_url   | grep docker-compose-Linux-x86_64   | cut -d '"' -f 4   | wget -qi -
    7  curl -s https://api.github.com/repos/docker/compose/releases/latest   | grep browser_download_url   | grep docker-compose-Linux-x86_64   | cut -d '"' -f 4   | wget -qi -
    8  chmod +x docker-compose-Linux-x86_64
    9  sudo mv docker-compose-Linux-x86_64 /usr/local/bin/docker-compose
   10  chmod 777 /usr/local/bin/docker-compose
   11  docker-compose --version
   12  sudo curl -L "https://github.com/docker/compose/releases/download/1.24.0/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
   13  sudo chmod +x /usr/local/bin/docker-compose
   14  sudo ln -s /usr/local/bin/docker-compose /usr/bin/docker-compose
   15  docker-compose --version
   16  sudo apt install -y nodejs npm
   17  sudo npm install npm --global
   18  sudo apt -y install python-pip git pwgen vim
   19  sudo pip install requests==2.14.2
   20  docker-compose --version
   21  git clone --depth 50 https://github.com/ansible/awx.git
   22  cd awx/installer/
   23  pwgen -N 1 -s 30
   24  vi inventory 
   25  clear
   26  ls -lrt
   27  vi inventory 
   28  history
   29  ansible --version
   30  which python3
   31  ansible-playbook -i inventory install.yml
   32  vi inventory 
   33  ansible-playbook -i inventory install.yml
   34  vi inventory 
   35  ansible-playbook -i inventory install.yml
   36  vi inventory 
   37  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python3"
   38  vi inventory 
   39  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python3"
   40  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
   41  pip install docker
   42  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python3"
   43  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
   44  pip install docker-compose
   45  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
   46  which python3
   47  history
   48  docker ps
   49  exit
   50  echo "deb http://ppa.launchpad.net/ansible/ansible/ubuntu bionic main" | sudo tee /etc/apt/sources.list.d/ansible.list
   51  sudo apt-key adv --keyserver keyserver.ubuntu.com --recv-keys 93C4A3FD7BB9C367
   52  sudo apt update
   53  sudo apt install -y ansible
   54  sudo apt -y install apt-transport-https ca-certificates curl gnupg-agent software-properties-common
   55  sudo apt remove docker docker-engine docker.io containerd runc
   56  curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo apt-key add -
   57  sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable"
   58  echo "deb [arch=amd64] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list
   59  sudo apt update
   60  sudo apt install docker-ce docker-ce-cli containerd.io
   61  echo $USER
   62  sudo usermod -aG docker $USER
   63  newgrp docker
   64  exit
   65  ls -lrt
   66  cd awx/
   67  ls -lrt
   68  cd installer/
   69  clear
   70  cat inventory 
   71  vi inventory 
   72  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
   73  clear
   74  pwd
   75  ssh-keygen
   76  cat ~/.ssh/id_rsa.pub 
   77  clear
   78  ls -lrt
   79  ping 192.168.32.10
   80  ssh 192.168.32.10
   81  clear
   82  ls- lrt
   83  cat ~/.ssh/id_rsa
   84  exit
   85  ls- lrt
   86  ls -lrt
   87  cat ~/.ssh/id_rsa
   88  cat ~/.ssh/id_rsa.pub 
   89  clear
   90  ssh 192.168.32.10
   91  ping 192.168.32.10
   92  cd
   93  cd .ssh/
   94  ls -lrt
   95  cat id_rsa.pub 
   96  ssh 192.168.32.10
   97  cat id_rsa.pub 
   98  ssh 192.168.32.10
   99  ls -lrt
  100  rm known_hosts 
  101  clear
  102  ls -lrt
  103  ssh 192.168.32.10
  104  cd cd awx/
  105  cd awx/
  106  ls -lrt
  107  cd installer/
  108  ls -ltr
  109  vi inventory 
  110  clear
  111  cat inventory 
  112  exit
  113  ckear
  114  clkear
  115  clear
  116  ls -lrt
  117  docker ps
  118  history
  119  nsible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
  120  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
  121  cd
  122  ls -lrt
  123  cd awx/
  124  ls -lrt
  125  cd installer/
  126  ls -lrt
  127  nsible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
  128  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
  129  exit
  130  clear
  131  ls -lrt
  132  history
  133  hostname -i
  134  hostname -f
  135  docker ps
  136  cd awx
  137  ls -lrt
  138  cd installer/
  139  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
  140  docker ps 
  141  clear
  142  ls -lrt
  143  cd
  144  cd .ssh/
  145  ls -lrt
  146  cat id_rsa.pub 
  147  clear
  148  which docker
  149  whuch ansible
  150  which ansible
  151  ls 0-lrt
  152  ls -lrt
  153  cd caw
  154  cd awx
  155  ls -lrt
  156  cd installer/
  157  ls -lrt
  158  cat install.yml 
  159  docker ps
  160  history
  161  ansible-playbook -i inventory install.yml -e "ansible_python_interpreter=/usr/bin/python"
  162  pwd
  163  cd ..
  164  ls -lrt
  165  p[wd
  166  pwd
  167  git remote -v
  168  git remote rm origin
  169  git remote add origin https://github.com/BTAPPS-R/awx-tower.git
