# Rusty Web Server

A simple HTTP web server implementation in Rust for learning purposes. This project demonstrates basic web server functionality using Rust's standard library.

## Features

- Basic HTTP/1.1 server implementation
- Handles GET requests
- Serves static HTML files
- Supports 200 OK and 404 Not Found responses
- Single-threaded request handling

## Prerequisites

- Rust (latest stable version)
- Cargo (Rust's package manager)

## Getting Started

1. Clone the repository:

```bash
git clone https://github.com/yourusername/rusty-web-server.git
cd rusty-web-server
```

2. Run the server:

```bash
cargo run
```

The server will start listening on `127.0.0.1:7878`

## Project Structure

- `src/main.rs` - Main server implementation
- `index.html` - Home page
- `404.html` - Not found error page

## How It Works

The server:

1. Listens for incoming TCP connections on port 7878
2. Reads and parses HTTP requests
3. Serves the appropriate HTML file based on the request path
4. Returns HTTP responses with proper headers

## Learning Points

This project demonstrates several Rust concepts:

- TCP networking with `TcpListener` and `TcpStream`
- File I/O operations
- String manipulation
- Error handling
- Basic HTTP protocol implementation

## Future Improvements

- [ ] Multi-threading support
- [ ] Configuration file support
- [ ] More HTTP methods (POST, PUT, DELETE)
- [ ] Custom routing
- [ ] Static file serving
- [ ] Request logging

## License

This project is open source and available under the MIT License.

## Contributing

Feel free to open issues and submit pull requests to improve the project.
