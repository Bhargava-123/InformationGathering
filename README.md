# To perform information gathering techniques

## AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.

http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.


## OUTPUT:

![image](https://github.com/Bhargava-123/InformationGathering/assets/85554376/3f33b34f-3f5e-42ab-8dbf-ef42991af016)





## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:

![image](https://github.com/Bhargava-Shankar/InformationGathering/assets/85554376/c7abceda-7e1e-42e6-b917-fea4c09eeeca)



## Finding Hosting Company
get further detail by using ip2location.com website.
## Output:

![image](https://github.com/Bhargava-Shankar/InformationGathering/assets/85554376/f6c86cf9-907d-4138-89cd-309ad5148438)




## History of the website:
## Output:
https://web.archive.org/


![Screenshot from 2023-05-15 04-42-06](https://github.com/A-Thiyagarajan/InformationGathering/assets/118707693/192a1d85-246e-45ad-bcd0-0a70e209c601)




# Webserver Fingerprinting:

## Netcat:
```
nc 172.17.52.118 80
```
## Output:


![Screenshot from 2023-05-13 05-08-48](https://github.com/A-Thiyagarajan/InformationGathering/assets/118707693/7c38b307-51d1-45b5-85ec-751ed930ba9b)


## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:

![Screenshot from 2023-05-13 05-14-53](https://github.com/A-Thiyagarajan/InformationGathering/assets/118707693/4631c0fd-1296-4c74-82fa-8950c48c5a61)



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
## Output:

![Screenshot from 2023-05-15 04-48-16](https://github.com/A-Thiyagarajan/InformationGathering/assets/118707693/ab6e52ed-b1c2-4c7c-b4cb-edc75d6de5e6)

![Screenshot from 2023-05-15 03-56-55](https://github.com/A-Thiyagarajan/InformationGathering/assets/118707693/3daa0d6f-df5d-4571-bf8b-c2fe63bbc3cc)


## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:

![Screenshot from 2023-05-15 04-16-42](https://github.com/A-Thiyagarajan/InformationGathering/assets/118707693/a70e6db5-d324-4bee-80f9-9dfdf9b37338)




# Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:


![image](https://github.com/Bhargava-Shankar/InformationGathering/assets/85554376/ba3aac42-e175-4245-997a-592ae7b9c4b1)




## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:


![image](https://github.com/Bhargava-Shankar/InformationGathering/assets/85554376/05f25ead-1322-42fa-8e1b-a1c211effdc1)




## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:

![image](https://github.com/Bhargava-Shankar/InformationGathering/assets/85554376/840d896a-2158-4979-8e8c-388f75d51e8b)




## RESULT:
The information gathering techniques tools/procedure were  identified successfully
