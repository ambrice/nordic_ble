# nordic_ble
Nordic Semiconductor wireshark packet dissector for Bluetooth LE packets.

Based on code from: https://devzone.nordicsemi.com/blogs/750/ble-sniffer-in-linux-using-wireshark/

To build, install cmake and wireshark-dev or equivalent, then:
- mkdir build
- cd build
- cmake ..
- make
- make install

This installs the wireshark plugin into ~/.wireshark/plugins/
