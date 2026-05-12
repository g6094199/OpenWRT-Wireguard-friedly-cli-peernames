# OpenWRT Wireguard friendly cli peernames

many thanks to [ppmm](https://forum.openwrt.org/t/wireguard-friendly-peernames-on-cli/250011){:target="_blank"} from the OpenWRT forum for the inital idea. <br>

# Install
to use the script create a file on your OpenWRT device in /usr/bin/ called wg-friendly. <br>

> vi /usr/bin/wg-friendly

copy the script content into the file and 
make it executable with <br>

>  chmod +x wg-friendly

now the script can executed from everywhere with <br>
>  wg-friendly

and it will show the output of wg with the enhancement of the friendly peer names greped from the network config: <br>

![wg vs wg-friendly](wg-vs-wg-friendly.png "wg vs wg-friendly")
