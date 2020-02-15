# Files

This repository contains files built periodically (every 24h) by an instance of [qmcgaw/updated](https://github.com/qdm12/updated) running on my server.

## DNS

Several files are built for DNS resolving:

- [named.root.updated](https://github.com/qdm12/files/blob/master/named.root.updated) contains information on root name servers, built from internic.net
- [root-anchors.xml.updated](https://github.com/qdm12/files/blob/master/root-anchors.xml.updated) contains the root anchors data in XML format, built from data.iana.org
- [root.key.updated](https://github.com/qdm12/files/blob/master/root.key.updated) contains the root keys and is used notably by Unbound, built from the XML root anchors

## Block lists

### Malicious

- [malicious-hostnames.updated](https://github.com/qdm12/files/blob/master/malicious-hostnames.updated) contains a list of unique malicious hostnames.
- [malicious-ips.updated](https://github.com/qdm12/files/blob/master/malicious-ips.xml.updated) contains a list of unique malicious IP addresses and CIDR ranges.

### Ads

- [ads-hostnames.updated](https://github.com/qdm12/files/blob/master/ads-hostnames.updated) contains a list of unique ads hostnames.
- [ads-ips.updated](https://github.com/qdm12/files/blob/master/ads-ips.xml.updated) contains a list of unique ads IP addresses and CIDR ranges.

### Surveillance

- [surveillance-hostnames.updated](https://github.com/qdm12/files/blob/master/surveillance-hostnames.updated) contains a list of unique surveillance hostnames.
- [surveillance-ips.updated](https://github.com/qdm12/files/blob/master/surveillance-ips.xml.updated) contains a list of unique surveillance IP addresses and CIDR ranges.
