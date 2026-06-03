# PID Control of Hybrid Electromagnetic Suspension (HEMS) Unit for MAGLEV Trains

<p align="center">
  <img src="Screenshot%202026-06-03%20220809.png" width="800">
</p>

## Overview

This project presents the design and simulation of a **PID-controlled Hybrid Electromagnetic Suspension (HEMS)** system for MAGLEV trains. The controller continuously regulates the levitation gap between the electromagnet and guideway, ensuring stable suspension, improved ride comfort, and enhanced operational safety.

## Objectives

- Design a Hybrid Electromagnetic Suspension system.
- Implement PID control for levitation gap regulation.
- Analyze system stability and dynamic response.
- Minimize overshoot and steady-state error.
- Evaluate performance under external disturbances.

## Result
<p align="center">
  <img src=".png" width="800">
</p>

## System Architecture

```text
Reference Gap
      │
      ▼
 +-----------+
 | PID       |
 | Controller|
 +-----------+
      │
      ▼
 Electromagnet
      │
      ▼
 Levitated Mass
      │
      ▼
 Gap Sensor
      │
      └────────── Feedback
