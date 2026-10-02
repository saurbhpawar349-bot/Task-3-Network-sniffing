# Task-3-Network-sniffing
# Task 03 – Network Sniffing

## Objective
To capture and analyze network traffic in an authorized local lab environment.

## Lab Environment
- Kali Linux
- Wireshark
- DVWA
- Docker
- Localhost HTTP environment

## Activities
- Captured local network traffic using Wireshark.
- Generated HTTP traffic from the local DVWA application.
- Applied HTTP display filters to identify HTTP requests.
- Observed how unencrypted HTTP traffic can expose request data.

## Security Observation
HTTP does not provide encryption for application data. Sensitive information transmitted over plain HTTP can potentially be observed by someone able to capture the traffic.

## Mitigation
Use HTTPS/TLS for web applications and avoid transmitting sensitive information over unencrypted HTTP.

## Evidence
- wireshark-capture.png
- http-traffic.png
- dvwa-login-traffic.png
