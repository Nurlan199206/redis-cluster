redis version: 7.0.4-1rl1~focal1

redis-cli --cluster-replicas=1 --cluster create 192.168.0.131:6379 192.168.0.132:6379 192.168.0.133:6379
