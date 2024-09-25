# theHarvester - Intelligence Gathering Tool

## Introduction

**theHarvester** is an open-source intelligence-gathering tool designed to collect information such as subdomain names, email addresses, virtual hosts, open ports, banners, and employee names from various public sources like search engines and PGP key servers.

This tool is widely used for reconnaissance and provides essential details about a domain, making it a valuable resource in cybersecurity.

## How to Use

To use **theHarvester**, execute the following commands:

- **Display help:**  
  ```bash
  theHarvester -h

- **Search emails and subdomains for a specific domain:**
  ```bash
  theHarvester -d [domain name] -b [search engine / all] [options]

### Examples
- **1.List available options:**  
  ```bash
  theHarvester
- **2.Search for emails in a domain:**  
  ```bash
  theHarvester -d wonderhowto.com -b all
- **3.Search emails with a limit of results:**  
  ```bash
  theHarvester -d wonderhowto.com -b all -l 200
- **4.Save the result to an HTML file:**  
  ```bash
  theHarvester -d microsoft.com -b all -h myresults.html
- **Search only in PGP:**  
  ```bash
  theHarvester -d microsoft.com -b pgp 

  
