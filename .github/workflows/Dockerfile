# Use an official lightweight image
FROM alpine:latest

# Set environment variables
ARG REPO_NAME
ARG BRANCH_NAME
ENV REPO_NAME=${REPO_NAME}
ENV BRANCH_NAME=${BRANCH_NAME}

# Install basic dependencies (optional)
RUN apk add --no-cache bash

# Default command to keep the container running
CMD ["sh", "-c", "echo Repo: $REPO_NAME, Branch: $BRANCH_NAME && tail -f /dev/null"]
