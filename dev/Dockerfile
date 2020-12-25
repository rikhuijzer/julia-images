FROM julia:buster

RUN set -eux; \
  apt-get update; \
  apt-get install -y --no-install-recommends \
    bash \
    build-essential \
    cmake \
    gfortran \
    git \
    libatomic1 \
    perl \
    python3 \
    wget \
    ; \
  rm -rf /var/lib/apt/lists/*

RUN git clone https://github.com/julialang/julia; \
  cd julia; \
  make test-path;

CMD ["bash"]
