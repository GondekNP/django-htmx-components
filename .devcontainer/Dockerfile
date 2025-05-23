FROM node:18

# Install make for the build commands
RUN apt-get update && apt-get install -y make

# Set working directory
WORKDIR /workspace

# Create a non-root user
ARG USERNAME=node
ARG USER_UID=1000
ARG USER_GID=$USER_UID

# Command to keep container running
CMD ["sleep", "infinity"]