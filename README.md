# Lonero-Blockchain-Explorer
Blockchain explorer for Lonero.

#### Installation

1) It takes data from the daemon config. It should be accessible from the Internet. Run the daemon with an open port as follows:
```bash
./forknoted --config-file lonero.conf--restricted-rpc --enable-cors=* --enable-blockchain-indexes --rpc-bind-ip=0.0.0.0 --rpc-bind-port=34415
```
2) Just upload to your website and change 'api' variable in config.js to point to your daemon.
