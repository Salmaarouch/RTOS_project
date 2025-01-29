FROM zephyrprojectrtos/zephyr-build:v0.27.4

USER root

RUN apt update
RUN apt install -y gdb
RUN apt install -y udev


USER user

RUN pyocd pack update
RUN pyocd pack install stm32h563zitx

RUN pip install -U dtsh