# FamilyNetworkAccess
a bundle of services to enable better network security, uptime, and data backups for my friends and family. General idea is to utilize Balena as a management platform, and Docker containers for managing content. 

Included in the scope:
- PiHole: to block adds and malicious traffic network-wide
- A VPN server (wireguard? openVPN?): to allow a "backdoor" into their local network for me to be able to assist w/ various local IT topics.
- Nextcloud Server: to allow users to upload media files (pictures, music, etc.) to a network storage device. I plan to use a 1TB SSD to assist with file storage and to be used as a "cache" in conjunction with:
- Federated Cloud Sharing: an App available for Nextcloud that should allow sharing of content between this "local" Nextcloud server and a "remote" server. In this case, the one on my unRAID NAS. Along with the local SSD, this should allow fast trasfer of data off of a computer or phone, but still allow large amounts of data to be backed up, without the users needing to invest in or manage a NAS.