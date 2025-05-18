# SPDX-License-Identifier: Apache-2.0

zephyr_library()

zephyr_library_sources(
  src/battery/battery.c
)

zephyr_include_directories(
  include PUBLIC
)
