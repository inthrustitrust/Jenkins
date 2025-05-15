FROM docker:20.10.24-cli

# Install OpenJDK 17 and Maven on Alpine
RUN apk add --no-cache \
    openjdk17 \
    maven \
    bash \
    git

ENV JAVA_HOME=/usr/lib/jvm/java-17-openjdk
ENV PATH=$JAVA_HOME/bin:$PATH

WORKDIR /app
