# OpenVPN for Docker

Based on [kylemanna/openvpn](https://hub.docker.com/r/kylemanna/openvpn) image.

### Server

```bash
bash vpn init [example.com]
bash vpn start
```

### Clients

All client certificates are located in `clients/[client-name].ovpn`

```bash
bash vpn add [client-name]
bash vpn remove [client-name]
```
