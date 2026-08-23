---
layout: post
title: Cross-Engine Humanoid Benchmark
accent_color: '#ccc'
theme_color: '#ccc'
invert_sidebar: false
---
# Cross-Engine Humanoid Benchmark

A benchmark comparing MuJoCo and PyBullet on the same 29-DoF Unitree G1 humanoid, running an identical scripted squat-and-recover task in both engines. It logs joint tracking RMSE, ground-reaction forces, center-of-mass deviation, wall-clock step time, and torque/energy, with statistics computed over 20 trials per engine.

Phase 2 goes further: it reuses a PSO-based sim-to-real calibration method from my SoftRobots research (CBA/CBIC 2025) to close the gap between the two engines, treating a handful of MuJoCo parameters as free variables and searching them against the PyBullet run as a reference — a 30.6% reduction in tracking/force error.

Everything is reproducible from a clean clone, with CI running the full benchmark on every push.

You can access the GitHub repository [here](https://github.com/tiago369/cross-engine-humanoid-benchmark).
