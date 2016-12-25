FROM node:6.9.2-alpine

MAINTAINER Dave <git@davidesaias.com>

# Install Yarn
RUN touch ~/.bashrc \
    && apk add --no-cache --virtual .build-deps tar curl bash gnupg \
    && curl -o- -L https://yarnpkg.com/install.sh | bash \
    && apk del .build-deps

ENV PATH /root/.yarn/bin:$PATH
