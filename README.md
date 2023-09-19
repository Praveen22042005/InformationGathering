# InformationGathering
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

## Pen Test Tools Categories:
Following Categories of pen test tools are identified for information gathering: Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network. http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## OUTPUT:
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/8f8de0c8-e3fd-428a-8716-9afe80311228)
## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
Output:
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/203297b9-a455-4372-8c50-12b8ff3eafc9)
Finding Hosting Company
get further detail by using ip2location.com website.
Output:
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/1c5d783a-5be0-44af-bb01-86d8ccc9a275)
## History of the website:
Output:
https://web.archive.org/
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/a13cc407-bd0e-448d-8f52-7057623831e1)
```
nc 172.17.52.118 80
```
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/1a2fab1a-8a90-42b0-bf5e-a8d494d9d988)
nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
Output:
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/a3941fab-e6c5-4ddc-a474-c0ac97384ffb)
## Whatweb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
Output:
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/be6f753c-39f6-4b70-97fb-b21e3c078a9f)
httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
Output:
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/b01fee44-0f87-420d-bdb5-2fedb4c80398)

## Tracing the Location
TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
Output:
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/06d718b6-0a6b-4b07-9a18-e699fbe5824f)

UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```

Output:
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/b942984c-d551-4684-8448-eb8c06c57f2e)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```

Output:
![image](https://github.com/Praveen22042005/InformationGathering/assets/112475766/cf1f9683-217a-451c-941f-a0412e1dfc55)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
