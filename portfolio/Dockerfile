FROM python:3.9-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the local index.html file to the working directory
COPY index.html ./

# Expose the port the server will listen on
EXPOSE 6060

# Specify the entrypoint to run the HTTP server
ENTRYPOINT ["python", "-m", "http.server", "6060"]
