## teamspeak server setup post-install via proxmox

# installer script
```bash -c "$(curl -fsSL https://raw.githubusercontent.com/community-scripts/ProxmoxVE/main/ct/teamspeak-server.sh)"```

# upon installation completion run below to get privilege key
```journalctl -u teamspeak-server.service```

# connect to server from client side and finish setup from there
