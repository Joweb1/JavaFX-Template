# Base image with Java SDK (used by Codespaces)
FROM mcr.microsoft.com/devcontainers/java

# Install libraries needed by JavaFX
RUN apt-get update && \
    apt-get install -y libgtk-3-0 libcanberra-gtk-module libx11-xcb1 && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
