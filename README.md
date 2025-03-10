# ThatsMyType
DNS enumeration through targeted RFC queries.

# Usage Instructions

1. Enter the path of the file containing target hostnames. This could be a list of hundreds or even thousands of domain names that you would like to resolve.
2. Select the DNS server to query. This could be a public resolver such as Google, or a private corporate DNS server that you are auditing.
3. Select the RFC type for your DNS queries. (ex: A, CNAME, PTR, MINFO, HINFO, ALL, ANY)
   - If you arent sure which option to use, the [IANA DNS Parameters](https://www.iana.org/assignments/dns-parameters/dns-parameters.xhtml) portal is a great place to start.

![image](https://github.com/user-attachments/assets/1c829dd9-0f86-47d0-9f67-5f73f5adf1c8)
Image Source: [Wikipedia](https://upload.wikimedia.org/wikipedia/commons/5/59/All_active_dns_record_types.png)
