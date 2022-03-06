# netPractice

Summary: This document is a System Administration related exercise.

<details>

<summary>Level_1</summary>
<p>
	<img src="https://raw.githubusercontent.com/Mustapha-Nawawi-T/netPractice/main/photos/Level_1.png" alt="image Level_1">
</p>

### to connect client A with client B the shold have same mask (255.255.255.0) thene the maske well split the ip address to tow parts (ip of the network and ip of the node or host) in these case the ip of the network is 104.96.23.0 so we have arange of ip we can use (104.96.23.1 to 104.96.23.254 the last one is for brodcatsting (104.96.23.255)) so we gave client A ip of (104.96.23.1) and clinet B ip of (104.96.23.12) ;

### to connect clinet D withe clint C we do the same then but these time we have mask of (255.255.0.0) so we have range (211.191.0.1 to 211.191.255.255) so we gave clinet D ip of (211.191.245.1) and clinet C ip of (211.191.245.75) ;

</details>

<details>

<summary>Level_2</summary>
<p>
	<img src="https://raw.githubusercontent.com/Mustapha-Nawawi-T/netPractice/main/photos/Level_2.png" alt="image Level_2">
</p>

### in these level we did like level_1 but we tested ip addresses like 127.0.0.1 (we can't use these addresses (127.0.0.0) to (127.255.255) becouse the are loop bach addresses)

### and also we work we the last maske we can use its (/30) it's same as (255.255.252) that we gave use just tow addresses that we need 0.0.0.1 and 0.0.0.2

</details>

<details>

<summary>Level_3</summary>
<p>
	<img src="https://raw.githubusercontent.com/Mustapha-Nawawi-T/netPractice/main/photos/Level_3.png" alt="image Level_3">
</p>

### we dide as the last tow levels but these time we have what cold a switch it's a divise that connect multiple devises to creat a large local area networl (LAN) and that devise operates in layer 2 becouse he is just work with MAC addresses 

</details>

<details>

<summary>Level_4</summary>
<p>
	<img src="https://raw.githubusercontent.com/Mustapha-Nawawi-T/netPractice/main/photos/Level_4.png" alt="image Level_4">
</p>

### in these level we descovered what called a router we use to connect multiple (LAN) to creat a Wide area network (WAN) and thats device operates in layer 3 becouse he work with ip address

## we shode not give the gate waye an ip thats arledy taken from an interface in same router

</details>

<details>

<summary>Level_5</summary>
<p>
	<img src="https://raw.githubusercontent.com/Mustapha-Nawawi-T/netPractice/main/photos/Level_5.png" alt="image Level_5">
</p>

### in these level we worked with routing table its useful to deside were to send a package for example we confige what is the destanation and the nexte hop in these case we use default destanation its workes if we have just one way to sande samthing (routers have tow entarface) or we need to send some thene to unknowk destanation like internet thats whates we dide in these case

</details>

<details>

<summary>Level_6</summary>
<p>
	<img src="https://raw.githubusercontent.com/Mustapha-Nawawi-T/netPractice/main/photos/Level_6.png" alt="image Level_6">
</p>

### in these levle we whant to connect with a server (8.8.8.8 DNS server of google) but we need to confige the routing table of the server to find hes way to use so we dont use default destanation but instad we put the subnet mask of our network (104.88.18.128/25) we can also (0.0.0.0/1) but the importent stuff is our network shod be part of that subnet mask so if we do ex (104.88.18.128/26) its well not work becouse our network not part of it

</details>

<details>

<summary>Level_7</summary>
<p>
	<img src="https://raw.githubusercontent.com/Mustapha-Nawawi-T/netPractice/main/photos/Level_7.png" alt="image Level_7">
</p>

### these level its a simple one ,  in these levle we just applay what we learned in last few levels , we have just tow routers to pass to rech A from C or C from A so we allwes do 2 hops to make cummunicatione between A and C

</details>

<details>

<summary>Level_8</summary>
<p>
	<img src="https://raw.githubusercontent.com/Mustapha-Nawawi-T/netPractice/main/photos/Level_8.png" alt="image Level_8">
</p>

### in these level we have to connect 2 network, we whant to connect theme with the internit, if we look at the routing table of internet 1 (157.111.65.0/26) thats mean that internit can only send to networks that in these subnet mask to solve these we devided that subnet mask to 4 smaller networks by adding 2 bits to the mask (/26 + 2 --> /28), we use 2 network of it and thats how internet can connect to differnt networks

### PS: the network that coonnect the 2 enterfaces of the router (yes it is als a network) need to be included also in the subnet mask of the internit   

</details>
