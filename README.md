# Laser_HTB [Portscanner]
Hackthebox | Laser | Autoexploiter


> I was bored so i went on hackthebox.eu, i did a box called 'laser' and to my suprise it was very hard..
> I needed to create a portscanner which made use of RPC calls and thats the only way i could discover this port since i use gopher://



## PORTSCAN.py
[!] Portscanner using RPC calls <br>
[+] Creating gRPC client <br>
[+] 1~65565 range scanning <br>
[+] Easy installation <br>


## INSTALLATION

### Linux (Ubuntu/Debian)

1) Clone this repo [Portscanner Install](https://github.com/EmirhanSarikaya/Laser_HTB.git) <br>
-> git clone https://github.com/EmirhanSarikaya/Laser_HTB.git <br><br>
2) Edit portscan.py to target ip & target port (9000 = <strong> cslistener </strong>)<br>
channel = grpc.insecure_channel('10.10.10.201:9000') <br>
3) python2 portscan.py 



### Mac

1) Clone this repo [Portscanner Install](https://github.com/EmirhanSarikaya/Laser_HTB.git) <br>
-> git clone https://github.com/EmirhanSarikaya/Laser_HTB.git <br><br>
2) Edit portscan.py to target ip & target port (9000 = <strong> cslistener </strong>)<br>
channel = grpc.insecure_channel('10.10.10.201:9000') <br>
3) python2 portscan.py 



### Windows

1) Install python2.7 (https://www.python.org/downloads/release/python-2718/)
2) Download this repo [Click me](https://github.com/EmirhanSarikaya/Laser_HTB.git) <br>
3) Edit portscan.py to target ip & target port (9000 = <strong> cslistener </strong>)<br>
channel = grpc.insecure_channel('10.10.10.201:9000') <br>
4) execute python2 portscan.py



*** MADE IN PYTHON 2.7 ***
