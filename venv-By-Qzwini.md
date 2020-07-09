# How to install virtualenv python in linux:

### First install pip
```Install PIP On Debian/Ubuntu```
    sudo apt install python3-pip	

```Install PIP on Arch Linux```
    pacman -S python-pip

### Install **pip** first

    sudo apt-get install python3-pip

### Then install **virtualenv** using pip3

    sudo pip3 install virtualenv 

### Now create a virtual environment 

    virtualenv venv 

>you can use any name insted of **venv**

  
### Active your virtual environment:    
    
    source venv/bin/activate
    

### To deactivate:

    deactivate
