# Sentinel 90-Day Learning Plan

This plan is designed to move from software experience into practical embedded/firmware engineering through hands-on work.

## Days 1–30 — Foundations

Focus:

- C fundamentals
- Compilation and debugging
- Basic electronics
- CoreS3 setup
- GPIO and simple inputs/outputs
- UART, I2C, and SPI concepts
- Reading datasheets
- Using a multimeter and logic analyzer

Deliverables:

- Sentinel v0.1 first boot
- Basic touchscreen/status UI
- At least one external sensor
- First logic-analyzer capture
- First documented intentional bug

## Days 31–60 — Real Firmware

Focus:

- ESP-IDF
- FreeRTOS tasks
- Queues and synchronization
- Interrupts and timers
- Persistent storage
- Wi-Fi communication
- Fault handling
- Watchdogs
- Better project structure

Deliverables:

- Multi-task Sentinel firmware
- Live sensor/status dashboard
- Local logging
- Peripheral health checks
- Wi-Fi telemetry
- Architecture diagram

## Days 61–90 — Portfolio System

Focus:

- Python hardware-in-the-loop testing
- Fault injection
- Automated validation
- Robotics integration
- Documentation
- Interview preparation

Deliverables:

- Python test harness
- Repeatable firmware tests
- Robotics/physical-system integration
- Fault and recovery demonstration
- Demo video
- Polished README and architecture documentation
- Resume-ready project bullets

## Weekly Rhythm

Aim for consistency rather than cramming.

- 4 shorter learning/build sessions during the week
- 1 longer hands-on build session
- 1 documentation/review session

Every session should leave behind evidence: code, notes, measurements, a commit, a diagram, or a documented lesson.

## Interview Goal

By the end of this plan, I should be able to explain:

- How memory and pointers work in C
- Why and when to use UART, I2C, or SPI
- How I debugged a real hardware communication problem
- How FreeRTOS tasks communicate safely
- How Sentinel handles failed peripherals
- How I tested firmware automatically
- How I designed the system and why I made specific tradeoffs
