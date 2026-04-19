<img width="883" height="666" alt="1000013249" src="https://github.com/user-attachments/assets/a542d2a5-d2e6-46e4-b746-67fba3e9840f" />
# Kray-Fi
A passive WiFi scanner built for Raspberry Pi. Scan nearby networks, check signal strength, watch connected devices and look up MAC vendors. No packet injection, no attacks. Just built for learning and visibility on your own network.
Built on a Pi 4 with a TP-Link USB adapter. Requires aircrack-ng, iw and ethtool.

Installation
Requirements: Raspberry Pi (or any Linux system), a WiFi adapter that supports monitor mode.

sudo apt install aircrack-ng iw ethtool ieee-data -y

Download the zip, extract it, then:

chmod +x kray-fi.sh
sudo bash kray-fi.sh

Or to run it from anywhere:

sudo cp kray-fi.sh /usr/local/bin/kray-fi
sudo chmod +x /usr/local/bin/kray-fi

Then just type kray-fi to launch.

Tips to support development and future projects: Ko-fi.com/kraynap

<img width="1003" height="721" alt="1000013248" src="https://github.com/user-attachments/assets/826103dc-e4a3-47cb-8717-f07b2a796372" />

