cmake_minimum_required(VERSION 3.4)
project(MultiWii_RF24)

set(CMAKE_CXX_FLAGS "${CMAKE_CXX_FLAGS} -std=c++11")

set(SOURCE_FILES
    Alarms.cpp
    Alarms.h
    config.h
    def.h
    EEPROM.cpp
    EEPROM.h
    GPS.cpp
    GPS.h
    IMU.cpp
    IMU.h
    LCD.cpp
    LCD.h
    MultiWii.cpp
    MultiWii.h
    NRF24_RX.cpp
    NRF24_RX.h
    Output.cpp
    Output.h
    Protocol.cpp
    Protocol.h
    RX.cpp
    RX.h
    Sensors.cpp
    Sensors.h
    Serial.cpp
    Serial.h
    types.h)

add_executable(MultiWii_RF24 ${SOURCE_FILES})