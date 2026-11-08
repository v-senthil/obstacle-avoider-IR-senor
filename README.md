# Obstacle Avoider (IR Sensor)

Arduino sketch for a two-wheel robot that steers around obstacles using two IR proximity sensors.

## How it works
- Left and right IR sensors are read as digital inputs (pins 7 and 6).
- Both clear → stop; left blocked → turn left; right blocked → turn right; both blocked → stop.
- Steering is driven by writing HIGH/LOW combinations straight to the motor driver inputs (pins 0–3).

## Hardware
- Arduino Uno/Nano
- 2x IR obstacle sensors
- L298N (or similar) motor driver + two DC motors

College project, 2019–2021.
