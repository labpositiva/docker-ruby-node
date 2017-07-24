FROM mhart/alpine-node:6.10.0

MAINTAINER Luis Mayta <@slovacus>

RUN apk add --update alpine-sdk \
    && apk --update add bash \
    ruby ruby-irb ruby-rake ruby-io-console \
    ruby-bigdecimal ruby-json ruby-bundler \
    libstdc++ tzdata bash ca-certificates \
    &&  echo 'gem: --no-document' > /etc/gemrc \
    && rm -rf /var/cache/apk/*

# Define default command.
CMD ["bash"]