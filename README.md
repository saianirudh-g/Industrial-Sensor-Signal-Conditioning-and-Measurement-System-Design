# Industrial Sensor Signal Conditioning and Measurement System Design

## Overview

This project presents the design and analysis of several industrial sensing and control systems commonly used in automation, instrumentation, and process-control applications.

The project combines PLC ladder logic, thermocouple temperature measurement, operational-amplifier signal conditioning, capacitive level sensing, strain-gauge load-cell analysis, and RTD-based temperature measurement.

The objective is to study how different sensors generate electrical signals and how those signals can be converted into useful engineering measurements such as temperature, liquid level, force, and control outputs.

---

## Project Title

**Design and Analysis of Industrial Sensors Using Thermocouples, RTDs, Load Cells, Capacitive Sensing, and PLC Ladder Logic**

---

## Objectives

The main objectives of this project are:

- Design PLC ladder logic for industrial pump control.
- Analyze a Type-S thermocouple using a thermocouple reference table.
- Calculate thermocouple temperature using NIST polynomial equations.
- Design an op-amp signal-conditioning system for a Type-J thermocouple.
- Analyze a capacitive liquid-level measurement system.
- Calculate the output of a strain-gauge load cell.
- Design an RTD bridge and op-amp measurement circuit.
- Convert low-level sensor signals into standardized voltage outputs.
- Evaluate sensor sensitivity, gain, linearity, and measurement accuracy.

---

# 1. PLC Pump Control Using Ladder Logic

## Problem Description

The first part of the project implements a PLC ladder-logic control system for pump `P604`.

The pump must turn ON when:

1. Toggle switch `SW601` is closed.

AND

2. Either limit switch `PS605` is open OR limit switch `PS607` is open.

The Boolean expression is:

```text
P604 = SW601 · (NOT PS605 + NOT PS607)
```

## Results
```
Cold junction EMF = 0.136618057 mV
Equivalent hot junction EMF = 18.036618057 mV
Hot junction temperature = 1707.83 C
```
