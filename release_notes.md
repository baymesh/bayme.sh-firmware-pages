# Baymesh Firmware

## Features

### MeshControl (Port 78)
Remote configuration via signed HMAC packets.

### Relay Node
- Broadcast relay_node: Specify which node rebroadcasts first
- DM relay_node preference

### Hop Limit
- HOP_MAX = 64

### Defaults
- Position broadcast: OFF by default
- Node info: Uses regular hop limit
- Channel slot: 49

## ⚠️ Not Compatible with Standard Meshtastic
This firmware is a custom fork. Only flash devices that will run Baymesh firmware.
