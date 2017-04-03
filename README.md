# dfw-drones

## Launch


### Remote ROS master connected trhough wifi

```bash
docker-compose -d wifi/docker-compose.yml up -d
```

### Local ROS master, mavlink stream trough serial port (xbee)

Configure the IP in `local/ros.env`

```bash
docker-compose -d local/docker-compose.yml up -d
```
