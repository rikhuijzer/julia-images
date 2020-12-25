FROM julia:buster

RUN set -eux; \
  apt-get update; \
  apt-get install -y --no-install-recommends \
    bash \
    build-essential \
    cmake \
    gfortran \
    libatomic1 \
    perl \
    wget \
    ; \
  rm -rf /var/lib/apt/lists/*

CMD ["bash"]
