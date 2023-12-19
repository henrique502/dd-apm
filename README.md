# Datadog local apm agent

Source: <https://github.com/DataDog/dd-apm-test-agent>

## Config

Configure local environment variables:

* `DD_AGENT_URL`=`http://127.0.0.1:8126`
* `DD_TRACE_AGENT_URL`=`http://127.0.0.1:8126`
* `DD_KEY`=`empty`

## Run

```sh
docker compose up -d
```

## See logs

```sh
docker logs --follow dd-apm-test-agent
```

## stop

```sh
docker compose down
```
