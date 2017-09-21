# Tokio Echo Server Example

## Build and Run

```bash
docker build -t rust-tokio-echo .
docker run -d -p 12345:12345 rust-tokio-echo
```

## Test

Try with `telnet localhost 12345`

<https://tokio.rs/docs/getting-started/simple-server/>
