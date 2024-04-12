## Information Gathering  
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:
![Screenshot 2024-04-12 102716](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/d99dc434-02fd-46ef-b42e-1f515fc1f86e)

## Finding ip address :
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:
![Screenshot 2024-04-12 102812](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/c22f1066-ca82-4891-8671-099e655b3ca3)
## Finding hosting company:
get further detail by using ip2location.com website.
## Output:
![Screenshot 2024-04-12 102859](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/3b01349d-4c19-41b1-8a55-b98a251c8484)
## History of the website :

## Output:
![Screenshot 2024-04-12 102911](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/47e9f068-71cf-4b04-8026-349a8abccde8)
## Netcat:
```
nc 172.17.52.118 80
```
## Output:
![Screenshot 2024-04-12 102922](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/dc87c0ec-7ed9-405c-8591-218f00a03e11)
## Nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:

![Screenshot 2024-04-12 102938](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/83582465-5c7d-4154-aa37-3e96fab85de9)
## Whatweb :
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
## Output:

![Screenshot 2024-04-12 102951](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/ddb5ed36-1f1e-4ae7-a037-c6f020a1b11e)
## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:
![Screenshot 2024-04-12 103004](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/6679b81b-53fb-432d-a352-1a942002f8a6)
## Tracing the location:
## TCP Traceroute:
```
 sudo traceroute -U www.saveetha.ac.in
```
## Output:
![Screenshot 2024-04-12 103015](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/d619ddfb-e7f0-4cfa-8416-ddc1e3bc629a)
## UDP Traceroute:
```
 sudo traceroute -U www.saveetha.ac.in
```
## Output:
![Screenshot 2024-04-12 103104](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/60f5e00f-b4df-47a6-bd29-be0c3679f21d)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:
![Screenshot 2024-04-12 103115](https://github.com/Gajalakshmivelmurugan/InformationGathering/assets/144871940/a84adb79-87a7-483d-997c-6155a4fd395e)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully

