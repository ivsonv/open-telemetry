# OPEN TELEMETRY & zipkin
- High-quality, ubiquitous, and portable telemetry to enable effective observability,
- Traces, Metrics, Logs, Create and collect telemetry data from your services and software, then forward them to a variety of analysis tools.
- https://opentelemetry.io

### Setup

start application go
- http://localhost:8888

```sh
cd goapp
docker compose up
go run main.go
```

start application in node.js
- http://localhost:3000

```sh
cd nodejs
npm i
node course.js
```

### Exports
- all scope of providers

https://github.com/open-telemetry/opentelemetry-collector-contrib/tree/main/exporter
![image](https://github.com/ivsonv/open-telemetry/assets/63156114/480ce0ae-4854-43bd-9a87-181c7fa4898f)


## zipkin
- All requisitions in `application go`

![image](https://github.com/ivsonv/open-telemetry/assets/63156114/00faa17f-ea02-411b-83ca-616fc4322a8f)

- Full flow involving `distributed` `tracing`

![image](https://github.com/ivsonv/open-telemetry/assets/63156114/e6fdde59-bfb2-4db7-aea0-a1ecb7c2d2f0)

