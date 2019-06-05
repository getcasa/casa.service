# Casa systemd service
Use casa with systemd.

## Install
```sh
sudo cp myservice.service /etc/systemd/system/casa.service
sudo chmod 644 /etc/systemd/system/casa.service
```

## Start
```sh
sudo systemctl start casa
```

## Launch at startup
```sh
sudo systemctl enable casa
```
