Example script to control Allone IR Blaster
Before you use this script you will need to setup the Allone using the WiWo App and give the Allone an IP address

You will also need to add some IR devices to the Wiwo app and make sure that they are controlled properly

Finally you will need to do a packet capture as you are pressing on the remote (one button at a time)

When looking for the UDP packet in wireshark, look for a packet with very long values as examples bellow

copy the value and remove the part with 686401326963 + mac address.
