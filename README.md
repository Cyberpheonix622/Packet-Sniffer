🛡️ Python Packet Sniffer
A low-level network packet sniffer written in Python using raw sockets. This tool captures Ethernet frames and decodes IPv4/IPv6, TCP, UDP, ICMP, and ICMPv6 protocols in real-time.

⚠️ For educational and ethical use only. Running this program requires root privileges.

📦 Features
Capture all network traffic on the host machine

Parse and display:

Ethernet headers

IPv4 and IPv6 packets

TCP, UDP, ICMP, ICMPv6 payloads

Real-time output of header info and data

Filter by protocol (TCP, UDP, ICMP)

🛠️ Prerequisites
Requirement	Notes
Python 3.x	Uses standard libraries only
Linux OS	Uses socket.PF_PACKET (Linux-only)
Root Privileges	Required to open raw sockets

🚀 Usage


🔧 1. Clone the repository
git clone https://github.com/yourusername/packet-sniffer-python.git
cd packet-sniffer-python


🧪 2. Run the sniffer
      sudo python3 sniffer.py


🧹 3. Optional: Filter by protocol
      sudo python3 sniffer.py TCP
      sudo python3 sniffer.py UDP
      sudo python3 sniffer.py ICMP
📂 File Structure
sniffer.py – Main sniffer script containing:

Ethernet frame parsing

IPv4/IPv6 support

TCP, UDP, ICMP, and ICMPv6 decoders

⚠️ Disclaimer
This tool is developed strictly for learning purposes in networking and cybersecurity.
Do NOT use it on networks without permission. Unauthorized use may be illegal.

📄 License
This project is open source and available under the MIT License.
