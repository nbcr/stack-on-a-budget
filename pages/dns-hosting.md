# DNS Hosting

<!-- TOC depthFrom:2 -->

- [FreeDNS](#freedns)

<!-- /TOC -->

<!-- TOC depthFrom:2 -->

- [LuaDNS](#luadns)

<!-- /TOC -->

## FreeDNS

[Features Page](https://freedns.afraid.org/signup/features/)

- Free tier: 5 domains, 20 records each, Free DNS, DDNS (Dynamic DNS), Static DNS.
- Pros: API, CNAME (Alias), A, AAAA, MX, NS, TXT, LOC, RP, HINFO, SRV, CAA records. IPv6 forward and reverse (.int and .arpa). URL cloaking. Change hosting provider without DNS propagation delays.
- Limitations: 20 subdomains on each of your domains that you point at this service. Can't use nameserver branding. You must share some subdomains with other users, you can specify which ones to not share. 1 Hour TTL. No wildcard support. Some ads. Limits on cloaking.
- Exceeding the free tier: You cannot exceed the free tier without paying first. Blocked by the site from creating too many subdomains.

## LuaDNS

[Pricing page](http://www.luadns.com/pricing.html)

* *Free tier*: 3 domains, 30 records, 50K queries/month (soft quota)
* *Pros*: API, git integration, Lua scripting, ALIAS records, email forwarding and HTTP redirects
* *Exceeding the free tier*: Upgrade to a paid package or migrate to another set of name servers with unmetered bandwidth
