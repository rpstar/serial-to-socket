# serial-to-socket
Python code to convert between a serial port and a socket targeted at Raspberry pi.

Goal is to provide a way for serial port data to be resent onto a
network socket and vice versa. Reason for this is to provide access to
serial port data for platforms to which a serial port cannot be hooked
up such as an iPad (at least easliy).   Bluetooth would be in theory
possible but it's either too hard (due to licensing) or too slow
(BLE).

