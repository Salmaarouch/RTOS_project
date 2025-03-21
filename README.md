# Prerequisites

- Install STM32 Cube Programmer for ST Link drivers

# How To

- west init -l manifest-repo
- west update
- west build EXAMPLEDIR --pristine -b nucleo_h563zi

# Hints

## PyOCD
west flash --runner pyocd

pyocd pack update
pyocd pack install stm32h563zitx

## Git Topology

T3: Forest topology yml

See KConfig in build/zephyr/.config