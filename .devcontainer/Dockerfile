# Use official Java + Maven image
FROM maven:3.8.8-eclipse-temurin-17

# Optional: Install JavaFX dependencies if needed
RUN apt-get update && \
    apt-get install -y libgtk-3-0 libcanberra-gtk-module libx11-xcb1 && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*
