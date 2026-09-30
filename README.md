# DFRP Wildfire Simulator

A real-time, browser-based 3D wildfire spread simulation running on WebGL via Three.js. It models surface fire propagation across procedurally generated terrain using 100,000 instanced vegetation units, spatial hash partitioning, dynamic wind vectors, slope pre-heating, and fuel moisture dynamics.

---

## Technical Overview

The simulation evaluates deterministic spread mechanics based on Rothermel surface fire equations, tracking live combustion, heat transfer, and evaporative moisture debt across large-scale instanced geometry at 60 FPS.
