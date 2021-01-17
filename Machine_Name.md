![](assets/images/banner.png)



<img src="assets/images/htb.png" style="margin-left: 20px; zoom: 60%;" align=left />    	<font size="10">Luanne</font>

​		17<sup>th</sup> Januray 2021

​		Machine Author(s): polarbearer

​		

 



### Description:

Luanne is an easy-level machine. 

### Difficulty:

`easy`

### Flags:

User: `<md5>`

Root: `<md5>`

# Enumeration


1) So first of all I perfomed an nmap scan on the machine which gave me the following results.

![](assets/images/Luanne_nmap.png)


2) We can see that its got an nginx server on port 80 which requires authentication (you can make out from the status code 401).

3) Robots.txt tells us we have a directory named weather. When we go to the route http://10.10.10.218/weather, we get a 404 not found error.

![](assets/images/Luanne_weather.png)


4) Hereafter I thought of performing a directory scan via gobuster to check if there are any other directories present. I found this...

![](assets/images/Luanne1.png)
 


# Foothold



# Lateral Movement



# Privilege Escalation

