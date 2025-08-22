## Setup & Building
```bash
cargo install cargo-watch
cargo build
``

## Run server locally (Manually)
```bash
cargo watch -q -c -w src/ -w assets/ -w templates/ -x run
```

visit http://localhost:8000

## Run server locally (Docker)
```bash
docker compose build
docker compose up
```

visit http://localhost:8000 
# app-service
