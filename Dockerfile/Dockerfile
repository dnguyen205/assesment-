# Image taking from --build-arg
ARG REGISTRY=10.10.10.10:5000
# base image using node:10.9-alpine
FROM ${REGISTRY}/node:9
ENV APP_DIR /app
ADD . $APP_DIR
RUN cd $APP_DIR && npm install

