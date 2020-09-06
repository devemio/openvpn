# OpenVPN server in Docker

Based on [kylemanna/openvpn](https://hub.docker.com/r/kylemanna/openvpn) image.

### 🔒 Server

```bash
# Run once
bash vpn init [domain.name]

bash vpn start
```

### 💡 Clients

All client certificates are located in `clients/[client-name].ovpn`

```bash
bash vpn add [client-name]
bash vpn remove [client-name]
```
