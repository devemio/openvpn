# OpenVPN server in Docker

Based on the [kylemanna/openvpn](https://hub.docker.com/r/kylemanna/openvpn) image.

### Server

#### Configure

Run once

```bash
bash vpn init [domain.name]
```

#### Start

```bash
bash vpn start
```

#### Stop

```bash
bash vpn stop
```

### Clients

All client certificates are located in `clients/[client-name].ovpn`

#### Add certificate

```bash
bash vpn add [client-name]
```

#### Remove certificate

```bash
bash vpn remove [client-name]
```
