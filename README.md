# Packet-Analyzer
Group Project 2022 - Packet Capture Analysis Tool - Given a series of packets, returns information about what they contain.

TO USE:
1. Run packet_analyzer.py
2. enjoy the fruits of your labor.
*This should work with any .pcap file, but the formatting will not be as pretty. It is designed to be uesd with the given files.

WHAT IT RETURNS:
1. Data size metrics (8 metrics)
  • Number of Echo Requests sent
  • Number of Echo Requests received
  • Number of Echo Replies sent
  • Number of Echo Replies received
  • Total Echo Request bytes sent
  • Total Echo Request bytes received
  • Total Echo Request data sent
  • Total Echo Request data received
  
2. Time based metrics (4 metrics)
  • Average Ping Round Trip Time (RTT)
  • Echo Request Throughput (in kB/sec)
  • Echo Request Goodput (in kB/sec)
  • Average Reply Delay (in microseconds)
  
3. Distance metrics (1 metric)
  • Average number of hops per Echo Request

Contributers:
  • Jillian Ebling (me)
  • Maple Reimer  
  • Josh Cohn
  • Ivan Chen
