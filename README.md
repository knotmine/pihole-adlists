# pihole-adlists

A blocklist file for Pihole to prevent IoT devices at home from crowding the LAN. 

## Steps

1. Create a [group](https://docs.pi-hole.net/group_management/example/)
2. Add the client device to the new group
3. Add the file url `https://raw.githubusercontent.com/knotmine/pihole-adlists/main/iot-blocklists.txt` to adlist
4. Assign the new adlist to the new group
