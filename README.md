## What this is
This repository summarises and reproduces key findings from my MSc thesis on
robotic grasp reliability under uncertainty (simulation + real hardware).

## The problem
Robotic pick-and-place systems often fail outside lab conditions.
The question is: which uncertainties actually matter?

## What I tested
- Object position uncertainty
- Gripper width uncertainty
- Velocity and acceleration uncertainty
- Combined uncertainty scenarios

## Key findings
- Object position uncertainty dominates grasp failure
- Small gripper miscalibration causes disproportionate failure
- Motion noise is largely absorbed by controllers in isolation
- Multiple small uncertainties compound into major failure

## Why this matters for real robots
Most systems over-optimize motion tuning and under-invest in perception
and calibration.

## What’s next
Ideas for extending this work (learning-based adaptation, online calibration, etc.)
