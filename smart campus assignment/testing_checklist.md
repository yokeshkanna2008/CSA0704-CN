# Testing Checklist
| Test | Target | Actual | Evidence |
|---|---|---|---|
| Ping | Success | | |
| ARP | Correct resolution | | |
| OSPF | Neighbour established | | |
| Link failure | <5 s convergence | | |
| DNS | <50 ms | | |
| TCP handshake | SYN/SYN-ACK/ACK | | |
| Wireless loss | <1% | | |
| TCP recovery | <2 RTT | | |

Wireshark filters: `arp`, `icmp`, `tcp`, `tcp.flags.syn == 1`, `dns`, `http`, `tls`.
