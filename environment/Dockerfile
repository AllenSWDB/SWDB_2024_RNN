# hash:sha256:697ff4f7a305b6abf8ee8731d93dee743fa0f51a8bcecb656a4737c51ab491b1
ARG REGISTRY_HOST
FROM $REGISTRY_HOST/codeocean/jupyterlab:3.0.9-miniconda4.9.2-python3.8-ubuntu20.04

ARG DEBIAN_FRONTEND=noninteractive

ARG GIT_ASKPASS
ARG GIT_ACCESS_TOKEN
COPY git-askpass /

RUN pip3 install -U --no-cache-dir \
    matplotlib==3.7.5 \
    numpy==1.24.4 \
    scikit-learn==1.3.2
