FROM node:12.8-alpine

WORKDIR /


# Path of the app within the docker container
ARG DOC_APP_PATH=/app

RUN yarn global add serve

# Copy over the package.json, and yarn.lock files
COPY . /app

# Expose container ports
EXPOSE 19002
EXPOSE 19006
EXPOSE 60710

# Set the current directory to tap repo
WORKDIR /$DOC_APP_PATH

# Run the start script
# Dont use the array syntax, so we have access to the DOC_CLI_PATH ENV
CMD [ "serve" ]