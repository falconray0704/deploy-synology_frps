# deploy-synology_frps
Deploy frps behind nginx by docker compose, which serving for synology in LAN.

If you want to customize the location of deploment, configure following variables in `.env`:

* `INSTALL_ROOT_PATH` :  Parent path for deployment.
* `SERVER_NAME`: Directory for deployment at INSTALL_ROOT_PATH .

```bash
./run.sh 
Usage:
./run.sh -c <cmd> -l "<item list>"
eg:
./run.sh -c deploy -l "frps_synology"
Supported cmd:
deploy
Supported items:
frps_synology
```

