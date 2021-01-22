# ktor-workshop-event-bus

The NATS Server has been used as an event bus
https://nats.io/

## Primal Commands

Start Server with Verbose Output and Monitor Port `8222`:
```
nats-server -m 8222 -V
```

Start NATS Streaming Server with Verbose Output and Monitor Port `8222`:
```
nats-streaming-server -m 8222 -V
```

Show NATS Server Process Info:
```
nats-top
```

Subscribe on subject `service1`:
```
nats-sub "service1"
```

Publish to subject `service1`:
```
nats-pub "service1" "Hallo Service 1"
```
