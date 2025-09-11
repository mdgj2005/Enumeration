# EXP NO :3
# NAME:M.GOKUL ANAND
# REGNO:212223040049

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

| Operator    | Description                        | Example Usage           |
| ----------- | ---------------------------------- | ----------------------- |
| `site:`     | Search within a specific domain    | `site:example.com`      |
| `inurl:`    | Search in URL                      | `inurl:admin`           |
| `intitle:`  | Search in page title               | `intitle:"index of"`    |
| `filetype:` | Search by file type                | `filetype:pdf`          |
| `intext:`   | Search inside page text            | `intext:"confidential"` |
| `link:`     | Pages that link to a specific site | `link:example.com`      |
| `cache:`    | View cached version of a site      | `cache:example.com`     |
| `ext:`      | Same as filetype                   | `ext:xls`               |

 ## Architecture 
 ```
+----------------------+
|   Attacker / Hacker  |
|   (Browser & Google) |
+----------+-----------+
           |
           | Google Dork Queries
           v
+---------------------------+
|       Google Search       |
+---------------------------+
           |
           | Indexed Public Content
           v
+---------------------------+
|   Target Websites / Data  |
| - Leaked files            |
| - Open directories        |
| - Sensitive info          |
+---------------------------+

```

# Output:
# SITE:
<img width="956" height="1062" alt="Site exp 3" src="https://github.com/user-attachments/assets/76b2ca96-32b4-42e1-b2b5-68e5879101e9" />

# INURL
<img width="956" height="1067" alt="inurl admin Exp3" src="https://github.com/user-attachments/assets/34f7c706-b367-430f-b29a-43e230499015" />

# INTITLE
<img width="950" height="1065" alt="intitle exp 3" src="https://github.com/user-attachments/assets/3b17d4f6-2685-407e-b54e-a39bd3ed00b1" />

# FILETYPE
<img width="953" height="1057" alt="file type" src="https://github.com/user-attachments/assets/e3ec0026-a26b-4bd8-bc60-7abd9cba2293" />

# INTEXT
<img width="948" height="1060" alt="Intext exp 3" src="https://github.com/user-attachments/assets/cba84167-8aea-4968-a265-744f126322bd" />

# LINK
<img width="952" height="1067" alt="Link exp 3" src="https://github.com/user-attachments/assets/fb5b6ab9-1f63-4f05-933b-992569cee612" />

# CACHE
<img width="952" height="1062" alt="Cache exp 3" src="https://github.com/user-attachments/assets/5f3950f1-01a5-43f9-8744-a0c203909d59" />

# EXT
<img width="948" height="1065" alt="ext exp 3" src="https://github.com/user-attachments/assets/f352a202-b5db-4cbe-9272-545626cf6c6a" />

# DNS Enumeration
<img width="951" height="827" alt="DNS enumeration exp 3" src="https://github.com/user-attachments/assets/f5ee8f6b-bcaa-408d-9e79-d2665cbc2304" />

## DNS Recon
<img width="953" height="541" alt="Dns recon exp 3" src="https://github.com/user-attachments/assets/2bdc4bda-0114-4422-95fe-13a53524df0b" />

| Record Type | Meaning                        | Example Output                   |
| ----------- | ------------------------------ | -------------------------------- |
| A           | Host to IPv4 address           | `example.com -> 93.184.216.34`   |
| AAAA        | Host to IPv6 address           | `example.com -> ::1`             |
| MX          | Mail server info               | `mail.example.com`               |
| NS          | Name servers                   | `ns1.example.com`                |
| TXT         | Misc data (SPF, verifications) | `v=spf1 include:_spf.google.com` |
| CNAME       | Canonical names (aliases)      | `www -> example.com`             |

## Common Tools Used (Kali Linux)

| Tool           | Description                                | Usage Example                           |
| -------------- | ------------------------------------------ | --------------------------------------- |
| `nslookup`     | DNS lookup tool (simple queries)           | `nslookup example.com`                  |
| `dig`          | DNS lookup utility (detailed)              | `dig example.com any`                   |
| `host`         | Simple DNS querying tool                   | `host example.com`                      |
| `dnsenum`      | Perl script to enumerate DNS info          | `dnsenum example.com`                   |
| `fierce`       | DNS scanner to locate non-contiguous IPs   | `fierce -dns example.com`               |
| `dnsrecon`     | Powerful DNS enumeration script            | `dnsrecon -d example.com -a`            |
| `theHarvester` | Subdomain enumeration using search engines | `theHarvester -d example.com -b google` |


## OUTPUT:
# NSLOOKUP
<img width="703" height="821" alt="NS lookup exp 3" src="https://github.com/user-attachments/assets/8a318853-1550-47f5-9346-58debc54f552" />

# DIG
<img width="758" height="667" alt="Dig exp 3" src="https://github.com/user-attachments/assets/1bf69d85-8c4d-43a5-910a-cd3923067fda" />

# HOST
<img width="737" height="527" alt="Host exp 3" src="https://github.com/user-attachments/assets/11c98ce8-af3d-4daa-b4d8-955b373359ea" />

# DNSSENUM
<img width="796" height="571" alt="dns senum exp 3" src="https://github.com/user-attachments/assets/72766944-196b-4d3c-a56d-dca153d68270" />

# DNSRECON
<img width="953" height="541" alt="Dns recon exp 3" src="https://github.com/user-attachments/assets/041795fd-400e-4a6a-acf1-51710ac9148c" />

# FIERCE
<img width="763" height="996" alt="fierce exp 3" src="https://github.com/user-attachments/assets/683ca218-93f0-49d8-9bfa-169d06cf2226" />

# HARVESTER
<img width="723" height="725" alt="Harvester exp 3" src="https://github.com/user-attachments/assets/be204124-6c7b-4dc7-a434-4d6c71cbccf9" />

## Architecture Diagram 
```
+-------------------+        +------------------+       +------------------+
|                   |        |                  |       |                  |
|   Attacker (You)  +------->|   Target Server   +<----->+    DNS Server    |
| Kali Linux / Parrot|       | (Mail / DNS Host) |       |  (Authoritative) |
+---------+---------+        +---------+--------+       +---------+--------+
          |                            ^                          ^
          |                            |                          |
          |                            |                          |
          |           +-----------------------------+            |
          |           |      Information Tools      |            |
          |           |-----------------------------|            |
          |           | smtp-user-enum              |            |
          |           | nmap --script smtp-enum-*   |            |
          |           | dnsenum                     |<-----------+
          |           +-----------------------------+
          |
          v
+-----------------------------+
|   Output/Report             |
|  - Usernames Found          |
|  - MX Records / Zones       |
|  - Subdomains / IPs         |
+-----------------------------+

```

## dnsenum
**Purpose:** A multithreaded Perl script to enumerate information from DNS servers.

**Use case:** Performs DNS zone transfers, brute force subdomains, and gather host IPs.

```
dnsenum example.com
```

## Output:
<img width="796" height="571" alt="dns senum exp 3" src="https://github.com/user-attachments/assets/bcd5ab09-0149-4fc3-bcd2-637783cfd763" />



## smtp-user-enum
**Purpose:** Standalone tool used to enumerate valid users by using the VRFY, EXPN, or RCPT TO commands.

**Use case:** Brute-forces SMTP to find users.

```
smtp-user-enum -M VRFY -U users.txt -t <target-ip>
```
  
 ## Output
<img width="930" height="513" alt="output 1 exp 3" src="https://github.com/user-attachments/assets/428a47c6-44d2-4a30-a7f6-97c79ef5a5bd" />




## nmap –script smtp-enum-users.nse <hostname>

**Purpose:** Uses smtp-enum-users NSE script to enumerate valid users on an SMTP server.

**Use case:** Helps identify email accounts on mail servers.

```
nmap -p 25 --script smtp-enum-users.nse <target-ip>
```
## OUTPUT:
<img width="843" height="176" alt="output 2 exp 3" src="https://github.com/user-attachments/assets/91830814-62fa-4dfd-afb7-c5739e27a062" />



## RESULT:
The Google hacking keywords and enumeration tools were identified and executed successfully
