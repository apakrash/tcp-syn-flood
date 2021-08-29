# tcp-syn-flood
This is for crafting and testing tcp syn packets to a destination in lab

### Python pre-requisite
'<addr>' apt install python3-scapy '<addr>'

python3 duplicate-syn-flood.py -t 1.1.1.1 -p 80 -c 5

Windows exe file
  
cd duplicate-syn-flood/
  
duplicate-syn-flood.exe -t 1.1.1.1 -p 8080 -c 5
  
Here
  
  -t = destination address
  
  -p = destination port
  
  -c = count

  src address is random
  
  ![image](https://user-images.githubusercontent.com/17419002/131242460-51bc5565-3e81-4158-96a2-696c91b7ab58.png)
