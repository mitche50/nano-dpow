# Nano DPoW Server

## Setup

### Requirements

1. Python 3.6.7 or higher.
2. A redis server running on `redis://localhost` by default.
3. An MQTT broker (tested with Mosquitto) running on `mqtt://localhost:1883` by default.
4. Authentication configured on the MQTT broker
5. Callbacks from a Nano node to `0.0.0.0:5030` by default.

### Installation

```bash
pip3 install -r requirements.txt
```

## Running

```bash
python3 dpow_server.py
```
