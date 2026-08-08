# Industrial Predictive Maintenance of High-Pressure Gate Valves

### Data-Driven Condition Monitoring using Time-Series Analysis and Advanced Signal Processing

MSc Applied Data Science in Engineering  
Glasgow Caledonian University

---

## Project Overview

This project investigates how data-driven analysis can provide deeper insight into the condition and performance of industrial high-pressure gate valves.

The work was completed as part of my MSc Applied Data Science in Engineering dissertation at Glasgow Caledonian University using experimental qualification-test data provided through an industrial collaboration with TechnipFMC.

The project combines low-frequency hydraulic test data with high-frequency vibration and magnetic sensor data to identify operational trends, degradation behaviour, anomalies, and potential condition-monitoring indicators.

Rather than relying only on conventional pass/fail qualification outcomes, the analysis explores how cycle-based KPIs and signal-processing techniques can provide a more detailed understanding of valve health.

---

## Project Scope

Two primary test programmes were analysed:

### Cyclic Pressure / Leakage Testing
- 5,000 psi gate valve
- 10,000 psi gate valve
- 15,000 psi gate valve
- 500 open-close cycles for each pressure class

### High-Frequency Vibration Testing
- 92 complete valve actuation cycles
- Tri-axial accelerometer data
- Magnetometer data
- Hydraulic pressure measurements
- Multi-day test programme

---

## Objectives

The project aimed to:

- Analyse repeated valve actuation cycles using time-series data.
- Extract engineering KPIs associated with sealing and operational behaviour.
- Identify degradation trends and anomalous operating conditions.
- Analyse high-frequency vibration signals for potential fault-sensitive characteristics.
- Investigate whether combining operational and vibration data can provide richer condition information than conventional pass/fail testing.

---

## Technologies & Methods

### Software
- MATLAB

### Data Analysis
- Time-Series Analysis
- Exploratory Data Analysis
- Cycle Segmentation
- KPI Extraction
- Data Visualisation

### Signal Processing
- Root Mean Square (RMS)
- Kurtosis
- Fast Fourier Transform (FFT)
- Power Spectral Density (PSD)
- Short-Time Fourier Transform (STFT)
- Spectrogram Analysis

### Engineering Application
- Predictive Maintenance
- Condition Monitoring
- Vibration Analysis
- Industrial Sensor Data Analysis

---

## Analytical Workflow

The analysis followed a structured workflow:

1. Data inspection and preprocessing
2. Signal cleaning and sensor alignment
3. Valve-cycle segmentation
4. KPI extraction
5. Time-series trend analysis
6. Time-domain vibration analysis
7. Frequency-domain analysis
8. Time-frequency analysis
9. Comparison of normal and anomalous behaviour
10. Engineering interpretation of the results

---

## Key Findings

The analysis identified several significant patterns across the test datasets:

- The 5k valve developed clear pressure-collapse and seat-leakage behaviour during the later stages of the 500-cycle qualification test.
- The 10k valve showed a distinct operating-condition change while ultimately passing qualification.
- The 15k valve demonstrated comparatively stable performance throughout its 500-cycle test.
- Valve opening and closing durations increased across the high-frequency test programme.
- RMS, kurtosis, PSD and STFT analysis revealed differences in vibration behaviour between operating cycles.
- Early vibration cycles exhibited highly impulsive behaviour before transitioning towards more sustained broadband vibration characteristics.
- Combining cycle-level operational KPIs with vibration analysis provided more diagnostic information than a binary qualification result alone.

---

## Engineering Relevance

High-pressure gate valves are critical isolation components used in demanding industrial applications.

Developing data-driven condition-monitoring techniques for these systems could support:

- Earlier identification of degradation
- Improved maintenance planning
- Reduced unexpected failures
- Better interpretation of qualification-test results
- Future predictive-maintenance and automated anomaly-detection systems

---

## Challenges Addressed

A major part of the project involved data engineering and preprocessing.

Challenges included:

- Very large sensor datasets
- Multiple sampling frequencies
- Missing or inconsistent metadata
- Sensor bias and gravity components
- Alignment of different sensor streams
- Identification of individual valve actuation cycles
- Interpretation of anomalous operating behaviour

These challenges required development of structured preprocessing and cycle-analysis workflows before meaningful signal analysis could be performed.

---

## Future Development

Potential extensions of the project include:

- Extending vibration analysis across the complete high-frequency dataset
- Automated anomaly detection
- Machine-learning-based valve condition classification
- Multi-sensor feature fusion
- Integration of pressure and vibration signatures
- Development of a more comprehensive valve-health assessment framework

---

## Repository Contents

```text
Industrial-Predictive-Maintenance-Gate-Valves/
│
├── README.md
│
├── docs/
│   ├── dissertation.pdf
│   └── presentation.pdf
│
└── images/
    └── selected-project-figures/
