# Enumeration
Enumeration Techniques

# Explore Google hacking and enumeration 

# AIM:

To use Google for gathering information and perform enumeration of targets

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various Google hacking keywords and enumeration tools as follows:


### Step 3:
Open terminal and try execute some kali linux commands

## Pen Test Tools Categories:  

Following Categories of pen test tools are identified:
Information Gathering.

Google Hacking:

Google hacking, also known as Google dorking, is a technique that involves using advanced operators to perform targeted searches on Google. These operators can be used to search for specific types of information, such as sensitive data that may have been inadvertently exposed on the web. Here are some advanced operators that can be used for Google hacking:

## site: 
This operator allows you to search for pages that are within a specific website or domain. For example, "site:example.com" would search for pages that are on the example.com domain.
Following searches for all the sites that is in the domain yahoo.com

![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/d4271e2a-20a0-42e7-a3d3-589da3ad4a88)

## filetype: 
This operator allows you to search for files of a specific type. For example, "filetype:pdf" would search for all PDF files.
Following searches for pdf file in the domain yahoo.com

![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/52683c53-a2fb-45d7-87fb-bc7ec734072b)


## intext: 
This operator allows you to search for pages that contain specific text within the body of the page. For example, "intext:password" would search for pages that contain the word "password" within the body of the page.

![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/b01de9d9-1987-4e99-8683-805e432b5ffc)



## inurl: 
This operator allows you to search for pages that contain specific text within the URL. For example, "inurl:admin" would search for pages that contain the word "admin" within the URL.

![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/16f47ada-45a5-4433-8692-2b380b0049a8)




## intitle:
This operator allows you to search for pages that contain specific text within the title tag. For example, "intitle:index of" would search for pages that contain "index of" within the title tag.

![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/4cc6617b-c2ca-470b-8f19-d98135e4debc)


## link: 
This operator allows you to search for pages that link to a specific URL. For example, "link:example.com" would search for pages that link to the example.com domain.

![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/4aa64017-383f-43da-91b6-f33141c369c6)


## cache: 
This operator allows you to view the cached version of a page. For example, "cache:example.com" would show the cached version of the example.com website.

![Screenshot (1388)](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/34df901d-496b-4d17-94c2-c7677fb6e73b)

## DNS Recon
![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/adb34cb9-8c3b-4331-8396-fa6456e555b1)

provides the ability to perform:
Check all NS records for zone transfers
Enumerate general DNS records for a given domain (MX, SOA, NS, A, AAAA, SPF , TXT)
Perform common SRV Record Enumeration
Top level domain expansion

## dnsenum
![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/ccdab9f4-11ce-4f8d-b3f5-0d0801e3329c)
![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/773e6e9f-3eae-4b7e-9aad-d801478d6046)

Dnsenum is a multithreaded perl script to enumerate DNS information of a domain and to discover non-contiguous ip blocks. The main purpose of Dnsenum is to gather as much information as possible about a domain. The program currently performs the following operations:

Get the host’s addresses (A record).
Get the namservers (threaded).
Get the MX record (threaded).
Perform axfr queries on nameservers and get BIND versions(threaded).
Get extra names and subdomains via google scraping (google query = “allinurl: -www site:domain”).
Brute force subdomains from file, can also perform recursion on subdomain that have NS records (all threaded).
Calculate C class domain network ranges and perform whois queries on them (threaded).
Perform reverse lookups on netranges (C class or/and whois netranges) (threaded).
Write to domain_ips.txt file ip-blocks.
This program is useful for pentesters, ethical hackers and forensics experts. It also can be used for security tests.


## smtp-user-enum
![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/d69570e4-961f-4f4a-a697-3bbc44a73635)

Username guessing tool primarily for use against the default Solaris SMTP service. Can use either EXPN, VRFY or RCPT TO.
In metasploit list all the usernames using head /etc/passwd or cat /etc/passwd:
select any username in the first column of the above file and check the same
## Telnet for smtp enumeration
Telnet allows to connect to remote host based on the port no. For smtp port no is 25
telnet <host address> 25 to connect
and issue appropriate commands

## nmap –script smtp-enum-users.nse <hostname>

#### The smtp-enum-users.nse script attempts to enumerate the users on a SMTP server by issuing the VRFY, EXPN or RCPT TO commands. The goal of this script is to discover all the user accounts in the remote system.


![image](https://github.com/VARSHINI22009118/Enumeration/assets/119401150/dfe562f3-03e8-4df5-8cbb-253c6639fdfc)


## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully

