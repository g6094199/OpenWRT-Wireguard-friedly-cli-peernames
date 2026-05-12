# OpenWRT Wireguard friendly cli peernames

Many thanks to [ppmm](https://forum.openwrt.org/t/wireguard-friendly-peernames-on-cli/250011) from the OpenWRT forum for the inital idea. <br>

# Install
To use the script create a file on your OpenWRT device in /usr/bin/ called wg-friendly. <br>

> vi /usr/bin/wg-friendly

Copy the script content into the file and 
make it executable with <br>

>  chmod +x wg-friendly

Now the script can executed from everywhere with <br>
>  wg-friendly

It will show the output of wg with the enhancement of the friendly peer names greped from the network config. <br>
He is an example of the output of wg va wg-friendly. <br>

![wg vs wg-friendly](wg-vs-wg-friendly.png "wg vs wg-friendly")
