---
layout: post
title: VLSM + CIDR Calculator
---

the objective of this tool is to facilitation calculate the VLSM and CIDR , the results output shown on terminal + in file (shown below).

![alt text](https://github.com/0xy4hy4/VLSM-CIDR/raw/master/ENG/1.png)

example :

adresse = 172.30.28.0/22

Site1R0 = 4 machines

Site1R1 = 50 machines

Site1R2 = 40 machines

Site1R3 = 100 machines

for the hosts it does not matter if you begain From the smallest to largest

0xy4hy4@0v3n_Sh3ll:$ python 0xy4hy4.py 172.30.28.0/22 4 50 40 100

after that put the names from who have largest value to smallest (Site1R3,Site1R1,Site1R2,Site1R0)

Put the names of the older ones at least : Site1R3,Site1R1,Site1R2,Site1R0 .

Appear in a file? Yes (Y) or No (n) :

Enter name with extenstion: ista.doc or .html .....etc

Filename : istaRN.doc

![alt text](https://github.com/0xy4hy4/VLSM-CIDR/raw/master/ENG/3.png)

![alt text](https://github.com/0xy4hy4/VLSM-CIDR/raw/master/ENG/2.png)
