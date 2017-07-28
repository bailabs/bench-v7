
## Installation

## Production Install

    apt-get update
    apt-get install python-minimal
    adduser frappe
    usermod -aG sudo frappe
    sudo -i
    su frappe
    curl "https://raw.githubusercontent.com/bailabs/bench-v7/master/install.py" -o install.py
    sudo python install.py --production

	
	
	
## Notes
Make sure socket.io version is 1.4.8

To check socket.io version
    npm list socket.io
   
To install socket.io version
    npm install socket.io@1.4.8

DigitalOcean Problem

    sudo rm -rvf /var/lib/apt/lists/*
