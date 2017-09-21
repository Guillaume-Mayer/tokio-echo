# Tokio Echo Server Example

<https://tokio.rs/docs/getting-started/simple-server/>

## Build and run with Docker

```bash
docker build -t rust-tokio-echo .
docker run -d -p 12345:12345 rust-tokio-echo
```

## Test with telnet

Try with `telnet localhost 12345`
