# factorio - headless server

This repo contains a quick and dirty script for downloading, installing, and setting up a systemd service for a factorio headless server.

See [official documentation](https://wiki.factorio.com/Multiplayer#Setting_up_a_Linux_Factorio_server) for more.

## contents
```
.
├── bin              // install binary
├── downloads        // headless server tarballs
└── factorio.service // systemd unit file
```

## setup
To setup, simply run:
```
sudo bin/install [version]
```