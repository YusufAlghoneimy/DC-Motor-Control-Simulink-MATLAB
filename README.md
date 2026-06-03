# DC Motor Speed Control using PID Controller

A Control Systems Lab project from German International University that models a DC motor and designs a PID controller to regulate its speed.

## Overview

The DC motor is mathematically modeled from its electrical and mechanical equations, yielding the open-loop transfer function:

$$G(s) = \frac{0.01}{0.005s^2 + 0.06s + 0.1001}$$

A PID controller was tuned using MATLAB's Control System Designer to meet the following specs:

| Specification | Requirement |
|---|---|
| Settling Time | < 2 s |
| Percent Overshoot | < 5% |
| Steady-State Error | ≈ 0 |

## Tuned PID Gains

| Parameter | Value |
|---|---|
| Kp | 79.7255 |
| Ki | 197.1274 |
| Kd | 6.5905 |

## Tools Used

- MATLAB & Simulink
- Control System Designer App

## Analysis Performed

- Open-loop & closed-loop step response
- Root locus (open & closed loop)
- Bode plot (gain margin, phase margin)
