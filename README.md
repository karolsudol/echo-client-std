# echo-client-std

## Usage

```bash
socat -v tcp-l:1234,fork exec:'/bin/cat'
```

```bash
cargo run
```

## Output

```
connecting to 127.0.0.1:1234
connected to echo server: 127.0.0.1:1234
Sent: "Hello World!"
Received: "Hello World!"
```
