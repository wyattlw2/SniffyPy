# SniffyPy

```CS438 (Communication Networks) Optional Project```

Running this project requires installing the Scapy library. Below are the installation commands:

sudo apt update
sudo apt install python3-scapy

You will also need to ensure your WiFi device is in monitor mode. To check this, run the following command:

iwconfig

If monitor mode is not enabled, running the following commands should enable it:

sudo ip link set wlan1 down
sudo iw wlan1 set monitor control
sudo ip link set wlan1 up