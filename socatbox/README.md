Useful to monitor conection management issue

```
2021/12/02 12:28:05 socat[1] N accepting connection from AF=2 127.0.0.1:43008 on AF=2 127.0.0.1:6379
2021/12/02 12:28:05 socat[1] N forked off child process 8
2021/12/02 12:28:05 socat[1] N listening on AF=2 0.0.0.0:6379
2021/12/02 12:28:05 socat[8] N opening connection to AF=2 10.128.2.84:6379
2021/12/02 12:28:05 socat[8] N successfully connected from local address AF=2 10.128.2.108:39302
2021/12/02 12:28:05 socat[8] N starting data transfer loop with FDs [6,6] and [5,5]
2021/12/02 12:28:06 socat[8] N socket 1 (fd 6) is at EOF
2021/12/02 12:28:06 socat[8] N socket 2 (fd 5) is at EOF
2021/12/02 12:28:06 socat[8] N exiting with status 0
2021/12/02 12:28:06 socat[1] N childdied(): handling signal 17
```

kubectl apply -f pod.yaml
