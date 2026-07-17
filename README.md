# RF Antenna Design Using ANSYS HFSS

## Overview

This repository contains a collection of antenna design and electromagnetic simulation projects developed using **ANSYS High Frequency Structure Simulator (HFSS)**.

The projects demonstrate the design, simulation, and performance evaluation of several commonly used antennas in wireless communication systems. Each design focuses on understanding antenna behavior through electromagnetic analysis and evaluating key performance metrics such as return loss, gain, directivity, bandwidth, radiation pattern, and impedance matching.

This repository serves as both a learning portfolio and a reference for RF engineering, antenna design, and wireless communication concepts.


## Repository Objectives

The objectives of this repository are to:

- Design various antenna types using ANSYS HFSS.
- Analyze antenna performance through electromagnetic simulation.
- Compare different antenna architectures and their applications.
- Develop practical experience in RF engineering and antenna optimization.
- Document simulation methodologies and results in a structured manner.


## Repository Structure

Each antenna project folder contains:

- HFSS project files
- Simulation screenshots
- Design parameters
- Exported simulation results
- Project documentation (design notes, results summary)

> New antenna designs are added by creating a new `<Antenna_Name>/` folder following the same internal structure and adding a corresponding entry to the table and sections below.

## Software and Tools
- ANSYS HFSS
- MATLAB
- Microsoft Excel
- Git & GitHub

## Design Methodology

Each antenna follows a common engineering workflow:

1. Selection of operating frequency.
2. Initial dimension calculations.
3. Antenna modeling in HFSS.
4. Material assignment.
5. Excitation and port configuration.
6. Boundary condition definition.
7. Mesh generation.
8. Electromagnetic simulation.
9. Performance evaluation.
10. Design optimization.

## Performance Metrics

All antenna designs are evaluated using the same standard set of RF performance metrics, enabling direct comparison across designs:

- Return Loss (S11)
- VSWR
- Gain
- Directivity
- Radiation Pattern
- Impedance Matching
- Bandwidth
- Surface Current Distribution
- Electric and Magnetic Field Distribution

## Antenna Designs

The table below summarizes all antenna designs currently in the repository. Each design has a dedicated section further down with a description, typical applications, and simulation outputs.

| Antenna | Folder | Description | 
|----------|--------|-------------|
| [Monopole Antenna](#monopole-antenna) | `Monopole_Antenna/` | Quarter-wave omnidirectional antenna |
| [Dipole Antenna](#dipole-antenna) | `Dipole_Antenna/` | Half-wave linear antenna |
| [Yagi-Uda Antenna](#yagi-uda-antenna) | `Yagi_Uda_Antenna/` | High-gain directional antenna |
| [Microstrip Antenna](#microstrip-antenna) | `Microstrip_Antenna/` | Planar antenna for wireless systems |
| [Patch Antenna](#patch-antenna) | `Patch_Antenna/` | Rectangular microstrip patch antenna |

Additional antenna designs will be added as the repository expands (see [Future Improvements](#future-improvements)).

### Monopole Antenna

A quarter-wave omnidirectional antenna, one of the simplest and most widely used antenna structures in wireless systems.

**Applications:**
- Mobile communications
- Vehicle antennas
- Base stations
- IoT devices

**Simulation outputs:** Antenna geometry, S11 (return loss), VSWR, gain plots, radiation pattern, surface current distribution, electric field distribution.

### Dipole Antenna

A half-wave linear antenna commonly used as a baseline reference design in RF and wireless communication education.

**Applications:**
- Radio communication
- Television broadcasting
- Wireless communication systems
- Educational RF laboratories

**Simulation outputs:** Antenna geometry, S11 (return loss), VSWR, gain plots, radiation pattern, surface current distribution, electric field distribution.

### Yagi-Uda Antenna

A high-gain directional antenna made up of a driven element, a reflector, and one or more directors, widely used where directional coverage is required.

**Applications:**
- Point-to-point communication
- Amateur radio
- Television reception
- Directional wireless links

**Simulation outputs:** Antenna geometry, S11 (return loss), VSWR, gain plots, radiation pattern, surface current distribution, electric field distribution.

### Microstrip Antenna

A low-profile planar antenna fabricated on a dielectric substrate, well suited to compact wireless devices.

**Applications:**
- GPS receivers
- Wi-Fi systems
- RFID
- Satellite communication
- IoT devices

**Simulation outputs:** Antenna geometry, S11 (return loss), VSWR, gain plots, radiation pattern, surface current distribution, electric field distribution.

### Patch Antenna

A rectangular microstrip patch antenna, a specific and widely deployed form of microstrip antenna optimized for narrowband, low-profile applications.

**Applications:**
- LTE networks
- 5G communication systems
- WLAN
- Aerospace systems
- Wireless sensor networks

**Simulation outputs:** Antenna geometry, S11 (return loss), VSWR, gain plots, radiation pattern, surface current distribution, electric field distribution.

## Future Improvements

Planned additions include:

- Circularly Polarized Patch Antennas
- MIMO Antennas
- Antenna Arrays
- Fractal Antennas
- Millimeter-Wave Antennas
- 5G Massive MIMO Antennas
- Beamforming Antenna Arrays
- Metamaterial-Based Antennas

## Learning Outcomes

Through these projects, the following competencies were developed:

- Electromagnetic simulation
- RF engineering fundamentals
- Antenna design principles
- Wireless communication systems
- HFSS modeling and analysis
- Performance optimization
- Technical documentation
- Engineering problem solving

## Related Topics

- Radio Frequency (RF) Engineering
- Antenna Theory
- Electromagnetics
- Wireless Communication
- Satellite Communications
- Microwave Engineering
- 4G LTE
- 5G Networks
- Internet of Things (IoT)

## License

This repository is intended for educational, research, and portfolio purposes. Feel free to explore the projects and adapt the methodologies for your own learning while respecting applicable licenses.
