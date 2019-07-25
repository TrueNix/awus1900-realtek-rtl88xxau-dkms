# awus1900-realtek-rtl88xxau-dkms
you should set monitor mode manually:

#/bin/bash

ip link set wlx00c0caa7582a down
iwconfig wlx00c0caa7582a mode monitor
ip link set wlx00c0caa7582a up
