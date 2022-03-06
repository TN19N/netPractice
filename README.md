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
