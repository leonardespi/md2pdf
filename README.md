# Markdown2PDF 

> Awesome Markdown to PDF!
```diff
- Online? Upload resume.md to stranger server?
+ Try Offline Web App!
```

## How to use md2pdf?
1. Click button choose `.md` file.
2. Edit in editor (left panel).
3. Click **Transform**!
4. Switch 'Destination' to **Save as PDF**.
4. **Chrome recommended**

## Using Docker

1. Install docker on your platform
2. Clone the repository
3. `cd` into `md2pdf`
4. Run `docker compose up -d` inside the directory

The docker compose binds the web server to `localhost:8080` by default. You can change this by finding the `ports` line in `docker-compose.yaml`.

**Note**: This docker compose uses the build directive, so your system will go build and optimize the code itself.
The application is hosted locally through nginx which is what binds to port 8080.
