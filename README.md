docker build -t ghcr.io/qchateau/website:latest .
docker run -d -p 3000:3000 ghcr.io/qchateau/website:latest
