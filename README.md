
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

	