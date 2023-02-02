# NW_Weiss

## 1. DHCP Server-Konfiguration aus einem Cisco Router auslesen
## 2. Router starten, einloggen und konfigurierte IP-Adressen auslesen
## 3. Konfiguration anzeigen
## 4. DHCP Konfiguration

# Protokol
   ADDRESS         NETWORK      INTERFACE
EDGE1
  - Ether2 = 192.168.23.0     /24
  - Wireguard1 = 172.17.72.0  /24
  - Ether3 = 10.105.64.0      /24
  - Ether1 = 192.168.122.0    /24
  
  Core1
   -Ether1 10.105.64.0        /30
   -Ether2 10.105.64.4        /30
   -Ether3 10.105.64.8        /30
   -Ether4 10.105.64.13       /30
  
 R1
  0 10.105.64.6/30   10.105.64.4   ether1
  1 10.105.0.1/24    10.105.0.0    ether2


SW2

`show ip interface brief`   
![grafik](https://user-images.githubusercontent.com/123244964/216193915-f1f12d43-0025-4790-ae9a-2620e183df42.png)   

`interface g3/0`   
![grafik](https://user-images.githubusercontent.com/123244964/216194975-e74e29aa-00d5-47d8-a6d7-10163fa3728f.png)
