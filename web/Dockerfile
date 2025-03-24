# Use Alpine as the base image
FROM alpine:latest

# Set working directory
WORKDIR /app

# Install Python and pip
RUN apk add --no-cache python3 py3-pip

# Copy local files to the container
COPY . /app

# Expose port 3000
EXPOSE 3000


# Specify the command to run the Python app (replace with your script)
CMD ["python3", "-m", "http.server", "3000"]
