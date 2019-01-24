FROM ubuntu

MAINTAINER vmuradia <vmuradia@student.42.us.org>

RUN apt-get update && apt-get upgrade -y && apt-get install -y nodejs npm git vim emacs

RUN npm install yarn --global && npm install npm --global

# How to build it?
# docker build -t a04 .

# How to run it?
# docker run --rm -ti a04
