###redis version: 7.0.4-1rl1~focal1

```redis-cli --cluster-replicas=1 --cluster create 192.168.0.131:6379 192.168.0.132:6379 192.168.0.133:6379```

```redis-cli -h 192.168.0.131 -p 6379 cluster nodes | grep master```

```redis-cli -h 192.168.0.131 -p 6379 cluster nodes```

```redis-cli --cluster check 192.168.0.131:6379```

```service redis-server restart```
