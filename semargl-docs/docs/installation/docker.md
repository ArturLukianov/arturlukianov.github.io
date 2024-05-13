**semargl** can be installed using Docker. However, some limitation should be considered. As we use `network: host` mode, not all protocols would be available. It is recommended to stick to TCP and HTTP(s) protocols.

# Building an image

Image of **semargl** can be build using following commands:
```bash
docker build -t latest .
```

# Running a docker-compose

We provide a ready-to-use docker-compose file. You can simply run:
```bash
docker compose up -d
```