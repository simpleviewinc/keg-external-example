FROM node:12.8-alpine

WORKDIR /

# Path of the app within the docker container
ARG DOC_APP_PATH=/app

# Port to run the app on
ARG DOC_APP_PORT=5000

# Install serve for a quick and easy server
RUN yarn global add serve

# Copy over the app into the image
COPY . /app

# Expose container ports
EXPOSE $DOC_APP_PORT

# Set the current directory to tap repo
WORKDIR /$DOC_APP_PATH

# Start the server
CMD [ "serve" ]