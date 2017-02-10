# graylog-content-pack-sonicwall
SonicWall Content Pack for Graylog

Tested with Graylog 2.1

This content pack provides extractors for SonicWall Firewalls and a few example dashboards:
* VPN Connections (24h)
* More coming soon (your help is welcome!)

## Includes

* Input SonicWall (Raw/Plaintext UDP)
* Extractors (Garbage Cleanup and KVP, dst_ip, dst_port, dst_if, dst_hostname, src_ip, src_port, src_hostname, proto_type, proto_service, timestamp)
* Dashboards

## Requirements

* Dell SonicWall Firewall configured to send SYSLOG to 12202/UDP, no custom settings
