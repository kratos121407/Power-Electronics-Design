# Power Electronics Design

A collection of power electronics simulation projects built in **MATLAB/Simulink**. Each project lives in its own repository and is linked here as a Git submodule, so this repo works as a single index of all the designs.

## Projects

### DC-DC Converters

| Project | Description |
|---|---|
| [DC-DC Buck Converter](https://github.com/kratos121407/dc-dc-buck-converter-simulink) | Step-down converter simulated in Simulink |
| [DC-DC Boost Converter](https://github.com/kratos121407/dc-dc-boost-converter-simulink) | Step-up converter simulated in Simulink |
| [DC-DC Buck-Boost Converter](https://github.com/kratos121407/dc-dc-buck-boost-converter-simulink) | Inverting step-up/step-down converter simulated in Simulink |

### Inverters (DC to AC)

| Project | Description |
|---|---|
| [Single-Phase Sine PWM Inverter](https://github.com/kratos121407/single-phase-sine-pwm-inverter) | Single-phase inverter using sinusoidal PWM switching |
| [Single-Phase Step-Controlled Inverter](https://github.com/kratos121407/single-phase-step-controlled-inverter) | Single-phase inverter with step (square-wave) control |
| [Three-Phase Step-Controlled Inverter](https://github.com/kratos121407/three-phase-step-controlled-inverter) | Three-phase inverter with step control |

### AC Controllers and Drives

| Project | Description |
|---|---|
| [Single-Phase AC Voltage Controller (Thyristor)](https://github.com/kratos121407/single-phase-ac-voltage-controller-thyristor) | AC voltage control using phase-angle firing of thyristors |
| [DC Motor Speed Control (PID)](https://github.com/kratos121407/dc-motor-speed-control-pid) | Closed-loop speed control of a DC motor with a PID controller |

## Tools Used

- MATLAB
- Simulink
- Simscape Electrical (Specialized Power Systems)

## Getting Started

### Clone with all projects

```bash
git clone --recurse-submodules https://github.com/kratos121407/Power-Electronics-Design.git
```

### Already cloned without submodules?

```bash
git submodule update --init --recursive
```

### Run a project

1. Open MATLAB and go to the project folder.
2. Open the `.slx` model file in Simulink.
3. Run any setup script (`.m` file) first if the project includes one.
4. Click **Run** and view the results in the Scope blocks.

See the README inside each project for details.

## Pulling the Latest Changes

When a project repo is updated, refresh the links here:

```bash
git submodule update --remote
git add .
git commit -m "Update submodules"
git push
```

## Repository Structure

```
Power-Electronics-Design/
├── dc-dc-buck-converter-simulink/
├── dc-dc-boost-converter-simulink/
├── dc-dc-buck-boost-converter-simulink/
├── single-phase-sine-pwm-inverter/
├── single-phase-step-controlled-inverter/
├── three-phase-step-controlled-inverter/
├── single-phase-ac-voltage-controller-thyristor/
└── dc-motor-speed-control-pid/
```

## Related

- [AI-ML-Projects](https://github.com/kratos121407/AI-ML-Projects): machine learning and AI projects

## Author

**kratos121407**
GitHub: [@kratos121407](https://github.com/kratos121407)
