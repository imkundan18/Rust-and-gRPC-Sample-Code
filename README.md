#gRPC
[dependencies]
tonic = "0.11.0"
prost = "0.12.4"
tokio = { version = "1.37.0", features = ["full"] }


[build-dependencies]
tonic-build = "=0.11.0"

[[bin]]
name="grpc-server"
path="src/server.rs"

[[bin]]
name="grpc-client"
path="src/client.rs"
