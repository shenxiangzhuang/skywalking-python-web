# Skywalking for Flask

## Quick Start

Setting the skywalking agent collector backend service address:

```bash
export SW_AGENT_COLLECTOR_BACKEND_SERVICES=172.17.0.2:12800
export SW_AGENT_PROTOCOL=http
export SW_AGENT_NAME=skywalking-python::flask
```

Start the application:
```bash
sw-python run python flask/app.py
```
