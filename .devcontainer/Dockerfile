FROM zephyrprojectrtos/zephyr-build:v0.27.4

USER root

RUN apt update
RUN apt install -y gdb

RUN pyocd pack update
RUN pyocd pack install stm32h563zitx

USER user