# RedTeam ToolSet -NetScan

![UI](https://www.naushad.co.uk/img/public/CyberScreen-RedTeam.gif)

# NetScan Interface
NetScan is a RedTeam Toolkit for Network Scan, Man in the Middle and Reverse Engineering. [Offensive and Defensive ToolSet]

![UI](https://www.naushad.co.uk/img/public/github/RedTeamNetScan.jpg)


## Prerequisites

* [Python](https://www.python.org) - Python Programming Language
* [Scapy](http://www.secdev.org/projects/scapy) - Interactive Packet Manipulation Program
* [Netzob](https://github.com/netzob/netzob) - Protocol Reverse Engineering, Modeling and Fuzzing

## Installing

Here is some Instructions for Installing Prerequisites,
Select Proper Instructions for your Operating System.

### Unix-like

1- Install Python3 and pip:

```
$ sudo apt-get install python3
$ sudo apt-get install python3-pip
```

2- Install Scapy:
```
$ cd /tmp
$ git clone https://github.com/phaethon/scapy
$ cd scapy
$ sudo python3 setup.py install
```

3- Install Netzob:
```
$ git clone https://github.com/netzob/netzob
$ cd ./netzob/
$ sudo apt-get install python3 python3-dev python3-setuptools build-essential
$ python3 setup.py install
$ python3 -m pip install bintrees --upgrade
```


### Windows

1- Install [python3](https://www.python.org)

2- Install Scapy:

2-1- Install [Winpcap](https://www.winpcap.org/install/bin/WinPcap_4_1_3.exe)

2-2- Install Scapy3k
```
python -m pip install scapy-python3
```

3- Install [Netzob](https://dev.netzob.org/projects/netzob/wiki/Installation_documentation_on_Windows)


## Authors

* **Naushad RedTeam** - *Initial work* - [Naushad007](https://github.com/Naushad007)
* email: naushad@owasp.com

## License

This project is licensed under the GNU General Public License v.01 - see the [LICENSE](LICENSE) file for details
