# SynthUx Academy Simple Board Multiplexer Daughterboard

This is a small PCB that is designed to fit on the perfboard section at the bottom right of the Simple Board from [SynthUX Academy](https://synthux.academy/simple). 

## Headers Explained

There are two headers on the board, one 2x8 header accepts all the analog inputs, while the 1x8 header provides connectivity to the Daisy Seed.  

### Analog Inputs Header
```
Pin   Mux IC  Channel
1	1   X0
2	1     X1
3	1     X2
4	1     X3
5	1     X4
6       1     X5
7	1     X6
8	1     X7
9	2     X0
10	2     X1
11	2     X2
12	2     X3
13	2     X4
14	2     X5
15	2     X6
16	2     X7
```

### Daisy Seed I/O Header
```
+ - positive voltage input-- connects  Pin 21 (AGND) of the Daisy Seed
A - Channel Select A
B - Channel Select B
C - Channel Select C
M1 - Mux 1 Out
M2 - Mux 2 Out
GND - ground -- connect to your Ground network (and Pins 20 and 40 on the Daisy Seed)
```  
Pin 7 on the I/O header is not used.  

## Bill of Materials  

```
2x CD4051 IC's in SOIC-16 format
2x 10nF capacitors in 0805 format
1x 2x8 female header with 2.54mm spacing
1x 1x8 female header with 2.54mm spacing  
4x single male pins for mounting the board
```

## Images  
![image](https://user-images.githubusercontent.com/1865305/191544070-62c89fff-17c7-4fe8-a8ae-150306176666.png)
![image](https://user-images.githubusercontent.com/1865305/191544110-2214a478-e132-42a9-abdd-603ba2018cf4.png)
![image](https://user-images.githubusercontent.com/1865305/191544143-cbe8cc9a-b70e-46df-b414-bfbaddad79a8.png)
