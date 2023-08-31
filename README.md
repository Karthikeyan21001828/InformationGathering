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

![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/c093cb7f-2ead-47ba-bf64-fcb11b82c464)





## Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## Output:

![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/1f99185a-9be3-4410-aca9-77181dc4df63)

## Finding Hosting Company
get further detail by using ip2location.com website.
## Output:

![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/2094c1c6-f0eb-41cc-8755-a54aa73d898b)

## History of the website:
## Output:
https://web.archive.org/


![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/e0953a57-7a2c-4c95-aadf-4b906ff9c01d)

# Webserver Fingerprinting:

## Netcat:
```
nc 172.17.52.118 80
```
## Output:


![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/71cbda81-8a47-4883-bd2e-e9ac8af731fa)


## nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## Output:

![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/97738d35-05ee-464f-b73b-870f56716073)

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

![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/835f4823-6883-4e7e-a406-499cacbcf633)

![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/cddc8a8c-832b-43b6-a3c9-5cafe4acece2)

## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## Output:

![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/a8fc4040-127f-4562-b4e4-b09c77743a9a)

# Tracing the Location
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## Output:


![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/23872367-200b-4a11-b21f-cac1a346e324)



## UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
## Output:

![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/d4f0c233-1715-41da-838c-054f0044fab4)

## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## Output:

![image](https://github.com/Karthikeyan21001828/InformationGathering/assets/93427303/34f8285f-ce1c-495e-af6d-462d1817f6d2)

## RESULT:
The information gathering techniques tools/procedure were  identified successfully
