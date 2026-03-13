# blackbox
blackbox            - buka
blackbox "help"     - langsung
blackbox configure  - pilih AI
blackbox login      - login
ctrl+c              - stop
ctrl+d              - EOF
 -------------------
# rust
   1 docker compose up -d
   2 docker compose exec rust bash
   3 docker run -it --rm -v $(pwd):/app rust:latest bash

   4 rustc --version
   5 cargo --version
   6 cargo search tokio
 -----------------------
 # dioxus
dx --version
dx create app
dx create app --template web
# jalankan pro dioxus
dx serve
cargo run
# build untuk prod
dx build --release
# membuat proj
    0.cargo install dioxus-cli
    1.dx new app
    2.rustup component add rustfmt
    3.rustup target add wasm32-unknown-unknown
    4.cd app
    5.dx serve --port 3000 --addr 0.0.0.0 # jika port docker 3000 only
    6.dx serve --addr 0.0.0.0 # jika port 8080 open, because default


