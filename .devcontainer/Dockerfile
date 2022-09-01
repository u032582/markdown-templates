FROM ghcr.io/u032582/ubuntu-devuser:latest

USER root
RUN apt-get update -qq && \
    DEBIAN_FRONTEND=noninteractive apt-get install -y \
    graphviz \
    && apt-get clean && rm -rf /var/lib/apt/lists/*

USER devuser
SHELL ["/bin/bash", "-c"]
RUN source "$HOME/.sdkman/bin/sdkman-init.sh" && sdk install java 17.0.4-oracle
