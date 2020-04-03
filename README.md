## Heimdall Monitoring

Monitor your Heimdall server with Prometheus and Grafana

## Follow below steps to set up monitoring on heimdall

step1:
```
enable prometheus falg on heimdall config.toml file
path = $HOME/.heimdalld/config
```
step2:
```
restart heimdall
```
step3:
```
start the both promethues and grafana containers
usage:
docker-compose up -d
```
step4:
```
Login to grafana dashboard and edit the datasource url to 
```
