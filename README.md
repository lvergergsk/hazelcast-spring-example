#### To run
- make sure `8081` ~ `8083` & `9701` ~ `9703` is available.
- make sure `172.28.1.1` ~ `172.28.1.3` is available
- run `docker-compose up -d --build`
- Management center available at `http://localhost:8084/hazelcast-mancenter`

#### Request example
##### Caching
- `curl 127.0.0.1:8081/api/v1.0/dummy/time/now`
- `curl 127.0.0.1:8081/api/v1.0/dummy/time/yesterday`
##### Executor
- `curl localhost:8081/api/v1.0/dummy/task/log`
