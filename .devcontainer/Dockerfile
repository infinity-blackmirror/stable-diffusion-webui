FROM mcr.microsoft.com/vscode/devcontainers/base:jammy

RUN --mount=type=cache,target=/var/cache/apt \
    apt-get -y update && \
    apt-get install -y google-perftools ffmpeg libsm6 libxext6
