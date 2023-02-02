# NW_Weiss

R1   
`ip route add gateway=10.105.64.5. dst-address=10.105.64.1/30`   

R3   
`ip default-gateway 10.105.64.13`   
`R3(config)#interface gigabitethernet 0/0`   
`R3(config-if)#ip address 10.105.64.14 255.255.255.252`   
`R3(config)#interface gigabitethernet 0/1`   
`R3(config-if)#ip address 10.105.64.1 255.255.255.252`   

SW2

`show ip interface brief`   
![grafik](https://user-images.githubusercontent.com/123244964/216193915-f1f12d43-0025-4790-ae9a-2620e183df42.png)   

`interface g3/0`   
![grafik](https://user-images.githubusercontent.com/123244964/216194975-e74e29aa-00d5-47d8-a6d7-10163fa3728f.png)   

SW3
`show ip interface brief`   

SW4   
`show ip interface brief`   
![grafik](https://user-images.githubusercontent.com/123244964/216198659-a1812dba-eb21-4a1c-839a-73ca21d47913.png)   

`interface g3/0`   
`interface g3/1`   
![grafik](https://user-images.githubusercontent.com/123244964/216200504-826f7f08-7818-4329-8d08-49b7b5ca0626.png)   

Server   
`sudo apt-get update`   
`sudo apt-get install bind9 bind9-doc`   
![grafik](https://user-images.githubusercontent.com/123244964/216208932-703d383c-330e-4a88-a5ee-cd76e5559966.png)   
![grafik](https://user-images.githubusercontent.com/123244964/216209341-98cd5497-9e94-4694-8380-857682b2a22a.png)   


 

