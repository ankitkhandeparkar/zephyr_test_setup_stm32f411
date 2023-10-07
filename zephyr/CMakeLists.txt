cmake_minimum_required(VERSION 3.13.1)
include($ENV{ZEPHYR_BASE}/cmake/app/boilerplate.cmake NO_POLICY_SCOPE)
project(test_zephyr_led_stm32f411)

FILE(GLOB app_sources ../src/*.c*)
target_sources(app PRIVATE ${app_sources})
