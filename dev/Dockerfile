FROM buster

RUN set -eux; \
  apt-get update; \
  apt-get install -y --no-install-recommends \
    bash
    build-essential \
    libatomic1 \
    gfortran \
    perl \
    wget \
    cmake \
    ; \
  rm -rf /var/lib/apt/lists/*

CMD ["bash"]
