# -------------------------------------------------------------------------------
# Protobuf-c - Protocol files generation
# (Forked from original repo to be adapted to Zephyr)
#
# Copyright (c) 2024 Hive-Zox International SA
# -------------------------------------------------------------------------------
zephyr_library()
zephyr_include_directories(.)
zephyr_library_sources(protobuf-c/protobuf-c.c)