---
title: Caribou web interface
# emoji: 🐳
emoji: /src/assets/icon.png
colorFrom: red
colorTo: blue
sdk: docker
app_port: 7860
---

# Caribou web

This is a web interface for running, monitoring and consulting results for the [Caribou analysis pipeline](https://github.com/bioinfoUQAM/Caribou).

The interface was built using Flet which is the official Flutter library for Python and the database was built using MongoDB.

Containerization is done using Docker and deployment on [DockerHub](https://hub.docker.com/r/nicdemon/caribou-metagenomics).

Hosting and computing are done on [HuggingFace Spaces](https://huggingface.co/spaces/nicdemon/caribou-metagenomics).

To deploy the app locally:
* Python:
```
flet run --web --port 8000
```
* Docker:
```
docker compose up
```

<!-- 
https://docs.docker.com/guides/
https://huggingface.co/docs/hub/spaces-sdks-docker
 -->