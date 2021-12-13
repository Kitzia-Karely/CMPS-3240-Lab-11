# CMPS-3240-Lab-11

| Skip Value | Max | Min | Average | Standard Deviation
| :--- | :--- | :--- | :--- | :--- |
| 127 | 226.719 Mbytes/sec | 215.093 Mbytes/sec | 222.296 |4.405|
| 128 |  220.753 Mbytes/sec |  209.715 Mbytes/sec  | 214.244 |3.944|
| 251 |  220.753 Mbytes/sec | 204.600 Mbytes/sec  |213.794 |4.042|
| 256 |  220.753 Mbytes/sec | 209.715 Mbytes/sec | 213.369|4.807|
| 509 |  220.753 Mbytes/sec | 209.715 Mbytes/sec| 213.324 |3.556|
| 512 | 215.093 Mbytes/sec | 209.715 Mbytes/sec | 211.081|3.295|
| 1021 | 174.763 Mbytes/sec | 161.319 Mbytes/sec | 168.999 |4.393|
| 1024 |199.729 Mbytes/sec | 190.650 Mbytes/sec | 192.885 |3.032|
| 2039 | 190.650 Mbytes/sec | 174.763 Mbytes/sec | 182.814 |4.921|
| 2048 | 195.084 Mbytes/sec |182.361 Mbytes/sec| 191.840 |4.525|
| 4093 |167.772 Mbytes/sec | 161.319 Mbytes/sec | 165.052 |2.324|
| 4096 | 195.084 Mbytes/sec | 182.361 Mbytes/sec | 190.763 |4.801|




```shell
while true; do echo "127" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  226.719 Mbytes/sec: 
Net Memory Bandwidth  226.719 Mbytes/sec: 
Net Memory Bandwidth  226.719 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
Net Memory Bandwidth  226.719 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
Net Memory Bandwidth  226.719 Mbytes/sec: 
```

```shell
while true; do echo "128" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
```

```shell
while true; do echo "251" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  204.600 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
```

```shell
while true; do echo "256" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  204.600 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
```

```shell
while true; do echo "509" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  220.753 Mbytes/sec: 
```

```shell
while true; do echo "512" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  215.093 Mbytes/sec: 
Net Memory Bandwidth  204.600 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
Net Memory Bandwidth  209.715 Mbytes/sec: 
```

```shell
while true; do echo "1021" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  174.763 Mbytes/sec: 
Net Memory Bandwidth  164.483 Mbytes/sec: 
Net Memory Bandwidth  164.483 Mbytes/sec: 
Net Memory Bandwidth  171.196 Mbytes/sec: 
Net Memory Bandwidth  171.196 Mbytes/sec: 
Net Memory Bandwidth  161.319 Mbytes/sec: 
Net Memory Bandwidth  174.763 Mbytes/sec: 
Net Memory Bandwidth  164.483 Mbytes/sec: 
Net Memory Bandwidth  171.196 Mbytes/sec: 
Net Memory Bandwidth  171.196 Mbytes/sec: 
Net Memory Bandwidth  171.196 Mbytes/sec: 
Net Memory Bandwidth  167.772 Mbytes/sec: 
```

```shell
while true; do echo "1024" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  199.729 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec:
```

```shell
while true; do echo "2039" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  178.481 Mbytes/sec: 
Net Memory Bandwidth  182.361 Mbytes/sec: 
Net Memory Bandwidth  178.481 Mbytes/sec: 
Net Memory Bandwidth  174.763 Mbytes/sec: 
Net Memory Bandwidth  178.481 Mbytes/sec: 
Net Memory Bandwidth  178.481 Mbytes/sec: 
Net Memory Bandwidth  186.414 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  186.414 Mbytes/sec: 
Net Memory Bandwidth  186.414 Mbytes/sec: 
Net Memory Bandwidth  186.414 Mbytes/sec: 
Net Memory Bandwidth  186.414 Mbytes/sec: 
```

```shell
while true; do echo "2048" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  186.414 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  182.361 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  186.414 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
```

```shell
while true; do echo "4093" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  164.483 Mbytes/sec: 
Net Memory Bandwidth  164.483 Mbytes/sec: 
Net Memory Bandwidth  167.772 Mbytes/sec: 
Net Memory Bandwidth  164.483 Mbytes/sec: 
Net Memory Bandwidth  164.483 Mbytes/sec: 
Net Memory Bandwidth  161.319 Mbytes/sec: 
Net Memory Bandwidth  167.772 Mbytes/sec: 
Net Memory Bandwidth  167.772 Mbytes/sec: 
Net Memory Bandwidth  164.483 Mbytes/sec: 
Net Memory Bandwidth  161.319 Mbytes/sec: 
Net Memory Bandwidth  167.772 Mbytes/sec: 
Net Memory Bandwidth  164.483 Mbytes/sec: 
```

```shell
while true; do echo "4096" | ./cache.out | grep Bandwidth; sleep 10; done
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  186.414 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  182.361 Mbytes/sec: 
Net Memory Bandwidth  195.084 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  190.650 Mbytes/sec: 
Net Memory Bandwidth  182.361 Mbytes/sec: 
```






