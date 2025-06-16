FROM alpine:latest

# Install bash (optional, if your script needs it)
RUN apk add --no-cache bash

# Copy your script into the container
COPY entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh

ENTRYPOINT ["/entrypoint.sh"]

