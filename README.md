# --==[ PcapOrNotPcap ]==--
## Description:
> PcapOrNotPcap is a script to parse the pcap file with scapy.

## How to install:
> 1. Download the script
> 2. Have a pcap file to parse
> 3. pip install scapy

## How to use:
> Usage: PcapOrNotPcap [-h] [-a] [-ip] [-p] [-m] [-u] [-ic] [-d] [-e] <file.pcap> <br>
> Options:<br>
> -h 				Show this message<br>
> -a 				General parsing <br>
> -ip 				Parse IP (IP src / IP dst), IP Layer<br>
> -p 				Parse ports (ports src / ports dst), TCP Layer<br>
> -m 				Parse MAC address (MAC src / MAC dst), Ether Layer<br>
> -u 				Parse ports (port src / ports dst), UDP Layer<br>
> -ic 				Parse icmp paquet, ICMP Layer<br>
> -d 				Parse data from paquets (all layer)<br>
> -e 				If executable find in data then try to export this in 'output' directory. (Bug with zipfile and password - soon implemented)<br>
