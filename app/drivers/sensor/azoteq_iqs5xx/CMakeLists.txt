# Copyright (c) 2022 The ZMK Contributors
# SPDX-License-Identifier: MIT

zephyr_include_directories(.)

zephyr_library()

zephyr_library_sources(iqs5xx.c)
zephyr_library_sources(iqs5xx_regdump.c)

