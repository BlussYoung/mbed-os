# Copyright (c) 2020 ARM Limited. All rights reserved.
# SPDX-License-Identifier: Apache-2.0

target_include_directories(mbed-ble
    INTERFACE
        .
        drivers
)

target_sources(mbed-ble
    INTERFACE
        Psoc6BLE.cpp
        drivers/IPCPipeTransportDriver.cpp
)
