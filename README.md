# Advanced Solar Tracking System

A Simulink model that simulates an solar tracking system designed to maximize energy capture under varying environmental conditions.

## Overview

This project models a solar tracking system that adjusts panel orientation to follow the sun, while accounting for real-world environmental disturbances such as cloud cover, temperature variation, and changing irradiance levels. The goal is to test how robust the tracking control performs under these non-ideal conditions.

## Tools Used

- **MATLAB Simulink** (built via MATLAB Online)

## How It Works

The model simulates the solar tracking control system, incorporating disturbance inputs (cloud cover, temperature, irradiance) to evaluate how the system maintains tracking accuracy and energy output despite environmental variability.

## Repository Structure
├── model/ → Simulink model file (Advanced_Solar_Tracker.slx)
├── results/ → Simulation output graphs (if available)
├── docs/ → Presentation deck and supporting materials
└── README.md

## Result

The system was simulated to evaluate tracking performance and energy capture efficiency under different environmental disturbance scenarios. See the presentation deck in `docs/` for detailed design explanation and results.

## How to Run

Open `Advanced_Solar_Tracker.slx` in MATLAB Simulink (R2021a or later recommended) and run the simulation.
