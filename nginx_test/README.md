## Тест с одним сервером

```
Document Path:          /api/v1/workspaces
Document Length:        805 bytes

Concurrency Level:      10
Time taken for tests:   7.114 seconds
Complete requests:      10000
Failed requests:        0
Total transferred:      9510000 bytes
HTML transferred:       8050000 bytes
Requests per second:    1405.68 [#/sec] (mean)
Time per request:       7.114 [ms] (mean)
Time per request:       0.711 [ms] (mean, across all concurrent requests)
Transfer rate:          1305.47 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    0   0.0      0       1
Processing:     1    7   6.2      4      31
Waiting:        1    7   6.2      3      31
Total:          1    7   6.2      4      31
```

## Тест с тремя серверами

```
Document Path:          /api/v1/workspaces
Document Length:        805 bytes

Concurrency Level:      10
Time taken for tests:   4.892 seconds
Complete requests:      10000
Failed requests:        0
Total transferred:      9510000 bytes
HTML transferred:       8050000 bytes
Requests per second:    2044.26 [#/sec] (mean)
Time per request:       4.892 [ms] (mean)
Time per request:       0.489 [ms] (mean, across all concurrent requests)
Transfer rate:          1898.53 [Kbytes/sec] received

Connection Times (ms)
              min  mean[+/-sd] median   max
Connect:        0    0   0.1      0       1
Processing:     1    5   5.3      3      32
Waiting:        1    5   5.3      3      32
Total:          1    5   5.3      3      32
```
