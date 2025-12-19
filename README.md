### pingRange_v5.ps1 - by knewyousir, 12/17/25
#### Scan a range of IPs with a simple ping scan to check if hosts are online
##### This script scans up to 1024 consecutive hosts.

##### sample usage: ./pingRange_v5.ps1 -StartIP <ipAddress> -ScanRange <int 1-1024>
##### Output both in console and in a log file

##### This was written to do simple ping-scans in an environment where no 3rd party ip scanning tools are permitted
