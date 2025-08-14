# Go Server Example

This is a simple Go web server that serves static files and handles basic routes.

## How to Run

1. **Install Go**  
   Make sure Go is installed on your system.  
   [Download Go](https://golang.org/dl/)

2. **Clone or Download the Project**  
   Navigate to the project directory:
   ```bash
   cd ~/go-server
   ```

3. **Run the Server**
   ```bash
   go run main.go
   ```
   The server will start on port `8080`.

## Available Pages and Paths

- **Home Page (Static)**
  - Path: [`/`](http://localhost:8080/)
  - File: `static/index.html`

- **Hello Handler**
  - Path: [`/hello`](http://localhost:8080/hello)
  - Responds with: `Hello, World!`

- **Form Page (Static)**
  - Path: [`/form.html`](http://localhost:8080/form.html)
  - File: `static/form.html`

- **Form Submission Handler**
  - Path: [`/form`](http://localhost:8080/form)
  - Method: `POST`
  - Displays submitted `name` and `address` values.

## Usage

- Visit [`http://localhost:8080/`](http://localhost:8080/) for the home page.
- Visit [`http://localhost:8080/form.html`](http://localhost:8080/form.html) to submit the form.
- Visit [`http://localhost:8080/hello`](http://localhost:8080/hello) for the hello handler.
