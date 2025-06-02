# Wireshark Traffic Analysis

## Task Summary
Captured and analyzed network traffic using Wireshark.

## Steps Followed
1. Installed Wireshark.
2. Captured traffic on active interface.
3. Visited websites and used ping to generate data.
4. Stopped capture after 1 minute.
5. Filtered packets by protocols (TCP, DNS, & HTTP).
6. Identified and analyzed 3 protocols.
7. Saved capture as `.pcap` file.
8. Documented the findings.

### Interface Used
- Wi-Fi

### Protocols Captured
1. **HTTP**
   - Source IP: 2401:4900:6677:64b1:bc37:6450:9523:f6a3
   - Destination IP: 2603:c021:4004:207a:50bf:11ec:5c55:f8aa
   - Method: POST
   - Host: example.com

2. **DNS**
   - Source IP: 192.168.24.215
   - Destination IP: 192.168.24.206
   - Query Name: chatgpt.com

3. **TCP**
   - Source IP: 2606:4700:83b2:7cbc:c2fd:370:5ff2:75c4
   - Destination IP: 2401:4900:6677:64b1:bc37:6450:9523:f6a3
   - TCP Flags: ACK
  



