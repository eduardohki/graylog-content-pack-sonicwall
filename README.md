# SonicWall Content Pack for Graylog
Tested with Graylog 2.1

This content pack provides extractors for SonicWall Firewalls and a few example dashboards:
* VPN Connections (24h)
* More coming soon (*help is welcome!*)

## Includes
* Input SonicWall (Raw/Plaintext UDP)
* Extractors (Garbage Cleanup and KVP, dst_ip, dst_port, dst_if, dst_hostname, src_ip, src_port, src_if, src_hostname, proto_type, proto_service, timestamp)
* Dashboards

  ### Tip
  The Dashboards use the "gl2_source_input" field in queries. Be sure to verify if it matches your SonicWall Input ID

## Requirements
* Dell SonicWall Firewall configured to send SYSLOG to 12202/UDP, no custom settings

## SonicWall Reference Guide
* Dell SonicWall Log Reference PDF: http://software.sonicwall.com/Manual/232-003262-00_RevA_SonicOS_6.2.5_LogEvents_ReferenceGuide.pdf
