# Sentinel

**Sentinel is an embedded learning platform.**

Sentinel is a hands-on embedded systems project built to grow from a simple M5Stack CoreS3 application into a polished portfolio project demonstrating firmware, hardware debugging, real-time systems, device telemetry, fault handling, and IoT integration.

The goal is not to follow tutorials forever. The goal is to learn embedded engineering by building, breaking, debugging, documenting, and improving a real system over time.

## Vision

Sentinel will become a portable embedded diagnostics and monitoring platform that can:

- Display live system and sensor information on the CoreS3 touchscreen
- Read external sensors and peripherals
- Communicate over GPIO, UART, I2C, and SPI
- Run multiple tasks using FreeRTOS
- Log events and diagnostic data
- Detect hardware or communication failures
- Recover gracefully from common faults
- Send telemetry over Wi-Fi
- Integrate with Python tooling and a backend/dashboard
- Eventually act as a diagnostic controller for other embedded devices or robotics projects

## Hardware

Primary device:

- M5Stack CoreS3 (ESP32-S3)

Learning/debugging equipment:

- Breadboard and electronic components
- External sensor/module kit
- 8-channel logic analyzer
- Digital multimeter
- ELEGOO UNO R3 Smart Robot Car Kit V4 (future robotics integration)

## Learning Goals

This project is designed to build practical skills in:

- C and C++
- Memory, pointers, arrays, structs, and bitwise operations
- ESP-IDF
- FreeRTOS
- GPIO
- UART
- I2C
- SPI
- Interrupts and timers
- Sensor drivers
- Embedded debugging
- Logic analyzer usage
- Fault handling and watchdogs
- Persistent storage
- Wi-Fi and IoT communication
- Python hardware-in-the-loop testing
- Technical documentation and system design

## Roadmap

### v0.1 — First Boot

- Set up the development environment
- Build and flash the first program
- Display `Sentinel v0.1` on the CoreS3 screen
- Print basic diagnostic output over serial
- Document the build/flash process

### v0.2 — Inputs and Outputs

- Add touchscreen or button input
- Control a simple output
- Introduce GPIO concepts
- Record the first intentional debugging exercise

### v0.3 — Sensors

- Connect an external sensor
- Read and display live values
- Learn basic I2C/SPI/UART concepts as needed
- Verify signals with the logic analyzer

### v0.4 — System Health

- Add a visual health/status screen
- Detect disconnected or failed peripherals
- Add useful diagnostic logging

### v0.5 — Real-Time Firmware

- Move core functionality into ESP-IDF
- Introduce FreeRTOS tasks
- Separate UI, sensor collection, logging, and communications

### v0.6 — Data and Connectivity

- Store events locally
- Add Wi-Fi connectivity
- Send telemetry to a backend
- Begin Python-based test tooling

### v0.7 — Fault Injection

- Intentionally create failures
- Detect timeouts and communication errors
- Add watchdog/recovery behavior
- Document root-cause analysis

### v0.8 — Hardware-in-the-Loop Testing

- Build a Python test harness
- Exercise firmware automatically over serial or Wi-Fi
- Generate repeatable test results

### v0.9 — Robotics Integration

- Integrate Sentinel with the ELEGOO robot platform
- Monitor sensors, motors, and subsystem health
- Display live diagnostics and fault states

### v1.0 — Portfolio Release

- Polish firmware and UI
- Create architecture diagrams
- Record a demonstration video
- Document design decisions, failures, fixes, and testing
- Prepare the project for technical interviews

## Engineering Philosophy

Sentinel follows a simple loop:

1. Build something small.
2. Observe what happens.
3. Break it intentionally or naturally.
4. Debug it.
5. Understand why it failed.
6. Fix it.
7. Document what was learned.
8. Add the next capability.

The project should remain understandable at every stage. Features are only valuable if their design and behavior can be explained clearly.

## Documentation

Project notes live in the `docs/` directory.

Each learning/build session should record:

- What I tried to build
- What I expected
- What actually happened
- Errors or unexpected behavior
- How I investigated the problem
- The root cause
- The fix
- What I learned
- What I want to try next

## Current Status

**Phase: Project initialization**

Next milestone: **Sentinel v0.1 — First Boot**

The first hands-on firmware work begins when the CoreS3 development environment is configured.
