# finding the real IPs behind cloudflare

### manually methods:

- [search.censys.io](search.censys.io): search for misconfigured stuff or grab the ssl key and throw that into:
- [crt.sh](crt.sh)

### auto methods:

- [hakoriginfinder](https://github.com/hakluke/hakoriginfinder): 
	searches an IP range for HTTP responses similar to that of the known site (levenshtein algorithm)
- [CloudFlair](https://github.com/christophetd/CloudFlair):
	Automates an internet-wide scan of Censys
