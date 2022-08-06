FROM paketobuildpacks/run:base-cnb

USER root

RUN apt update \
  && apt install -y --no-install-recommends fontconfig \
  && rm -rf /var/lib/apt/lists/*

USER cnb
