# ThatsMyType
DNS enumeration through targeted RFC queries.

# Usage Instructions

1. Enter the path of the file containing target hostnames. This could be a list of hundreds or even thousands of domain names that you would like to resolve.
2. Select the DNS server to query. This could be a public resolver such as Google, or a private corporate DNS server that you are auditing.
3. Select the RFC type for your DNS queries. (ex: A, PTR, MINFO, HINFO, ALL, ANY)
   - If you arent sure which option to use, refer the [IANA DNS Parameters](https://www.iana.org/assignments/dns-parameters/dns-parameters.xhtml) portal is a great place to start.
