# finding the real IPs behind cloudflare

### manually methods:

- [search.censys.io](https://search.censys.io/): search for misconfigured stuff or grab the ssl key and throw that into:
- [crt.sh](https://crt.sh/)

### auto methods:

- [hakoriginfinder](https://github.com/hakluke/hakoriginfinder): 
	searches an IP range for HTTP responses similar to that of the known site (levenshtein algorithm)
- [CloudFlair](https://github.com/christophetd/CloudFlair):
	Automates an internet-wide scan of Censys

---
presentation.md is playable via [lookatme](https://github.com/d0c-s4vage/lookatme)
