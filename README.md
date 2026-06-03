# DC Motor Speed Control using PID Controller
<img width="713" height="371" alt="image" src="https://github.com/user-attachments/assets/fe535e2f-1415-40de-adcc-6c70f1ae9890" />
<img width="884" height="822" alt="image" src="https://github.com/user-attachments/assets/e28abfb3-15d0-40b2-a1da-1bc2052cd5de" />
<img width="888" height="804" alt="image" src="https://github.com/user-attachments/assets/dec79c80-54ad-4ff1-bc2c-b304c4fd273a" />




## Overview

This is a simple Control Systems Lab project that was done in a single day. This project includes modelling a DC motor and designs a PID controller to regulate its speed. [Refer to the PDF attached for detailed explanation]


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
