# ThatsMyType

<img width="470" alt="ThatsMyType" src="https://github.com/user-attachments/assets/f0d19281-8848-4b25-bee4-ffa5905ac683" />

DNS enumeration through targeted RFC queries.

<img width="800" alt="ThatsMyType_2_Redacted" src="https://github.com/user-attachments/assets/d12e8212-e964-458d-8c1e-f89e05910b50" />

# Usage Instructions

1. Enter the path of the file containing target hostnames. This could be a list of hundreds or even thousands of domain names that you would like to resolve.
2. Select the DNS server to query. This could be a public resolver such as Google, or a private corporate DNS server that you are auditing.
3. Select the RFC type for your DNS queries. (ex: A, CNAME, PTR, TXT, MINFO, HINFO, ALL, ANY)
   - If you arent sure which option to use, the [IANA DNS Parameters](https://www.iana.org/assignments/dns-parameters/dns-parameters.xhtml) portal is a great place to start.
   - Results are saved in your working directory based on the type of query ran and the target resolver. (ex: resolutions-ALL-8.8.4.4.txt )
   - If the file already exists, ThatsMyType will append the existing file, so no results are lost.

![image](https://github.com/user-attachments/assets/1c829dd9-0f86-47d0-9f67-5f73f5adf1c8)
Image Source: [Wikipedia](https://upload.wikimedia.org/wikipedia/commons/5/59/All_active_dns_record_types.png)

# Testing Methodologies

I created a spreadsheet using the IANA resources provided from the webpage above. It has served me as a good reference for testing possible DNS types. 
The spreadsheet is available in the docs folder here.

<img width="1540" alt="IANA_References" src="https://github.com/user-attachments/assets/cc57d3ec-e851-4664-8058-b12d73b0d281" />



