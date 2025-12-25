# luaNDA
Tunnel mesh controlled by lua (non-discoverable activity).

This piece of software is a poor alternative to xray/vless, attempting to bypass roscompozor blocks by simulating regular http/https requests and utilizing lua runtime flexibility. Requires client and server parts to run the tunnel (though both can be combined in one process).

# TODO
* Implement PoC
* Develop native https server (currently http-only is supported)
* Add websockets support
* Dynamic peer blockage monitoring
* Packet manipulation in lua runtime
