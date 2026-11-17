
MOBILE COMPUTING – ASSIGNMENT 2 (CO2)

## Project Title
Python Simulation and Graphical Analysis of Mobile Communication and Multiple Access Techniques

## 1. Introduction

This project demonstrates important concepts in Mobile Computing and Mobile Telecommunication Systems using Python. It includes mathematical calculations, simulations, and graphical representations of different multiple access techniques.

The project covers:
- Mobile Communication and Mobile Computing
- Frequency Division Multiple Access (FDMA)
- Time Division Multiple Access (TDMA)
- Code Division Multiple Access (CDMA)
- Orthogonal Frequency Division Multiple Access (OFDMA)
- Space Division Multiple Access (SDMA)
- Comparison of Multiple Access Techniques
- OFDMA Resource Scheduling and Fairness

## 2. Objectives

- To understand the working principles of different multiple access techniques.
- To calculate the capacity of FDMA and TDMA systems.
- To analyse CDMA processing gain and Bit Error Rate (BER).
- To understand OFDMA subcarrier allocation and throughput.
- To visualize SDMA antenna beam patterns.
- To compare different multiple access techniques.
- To analyse throughput and fairness in OFDMA scheduling.

## 3. Technologies Used

- **Programming Language:** Python 3
- **Libraries:**
  - NumPy – Numerical calculations
  - Matplotlib – Graph generation
  - Pandas – Data analysis (optional)

## 4. Software Requirements

- Python 3.9 or above
- Visual Studio Code / PyCharm / Jupyter Notebook
- Required Python libraries

## 5. Installation

### Step 1: Install Python

Download and install Python from:

https://www.python.org/downloads/

### Step 2: Install Required Libraries

Open the terminal or command prompt and execute:

```bash
pip install numpy matplotlib pandas
```

### Step 3: Open the Project

Open the project folder in Visual Studio Code or any Python IDE.

## 6. Project Modules

### Module 1: Link Availability Analysis

- Calculates successful data delivery.
- Analyses packet failure probability.
- Calculates expected retry attempts.
- Displays delivery and retry-related graphs.

### Module 2: FDMA and TDMA Analysis

- Calculates the number of FDMA channels.
- Calculates the number of TDMA carriers and time slots.
- Compares nominal and adjusted resource capacity.
- Displays FDMA and TDMA comparison graphs.

### Module 3: CDMA Analysis

- Calculates CDMA processing gain.
- Converts processing gain into decibels.
- Analyses Bit Error Rate (BER).
- Displays CDMA performance graphs.

### Module 4: OFDMA Analysis

- Calculates OFDM symbol duration.
- Analyses subcarrier allocation.
- Estimates achievable data rates.
- Displays OFDMA resource allocation and throughput graphs.

### Module 5: SDMA Analysis

- Calculates antenna array factor.
- Analyses spatial beamforming.
- Displays antenna radiation patterns.

### Module 6: Multiple Access Comparison

- Compares FDMA, TDMA, CDMA, OFDMA and SDMA.
- Analyses advantages and limitations.
- Displays comparison graphs.

### Module 7: OFDMA Scheduler Analysis

- Allocates radio resources among multiple users.
- Calculates user throughput.
- Evaluates fairness using Jain's Fairness Index.
- Compares throughput and fairness.

## 7. How to Run the Programs

Run each Python program separately.

Example:

```bash
python module1_link_analysis.py
```

```bash
python module2_fdma_tdma.py
```

```bash
python module3_cdma.py
```

```bash
python module4_ofdma.py
```

```bash
python module5_sdma.py
```

```bash
python module6_comparison.py
```

```bash
python module7_scheduler.py
```

The graphs will be displayed in separate Matplotlib windows.

## 8. Important Formulas

### Link Availability

P(Success) = p

Expected number of attempts = 1/p

Expected failed attempts = (1-p)/p

### FDMA Capacity

Number of Channels = Total Bandwidth / Channel Bandwidth

### TDMA Capacity

Total Slots = Number of Carriers × Slots per Carrier

### CDMA Processing Gain

Gp = Chip Rate / Data Rate

Gp(dB) = 10 log10(Gp)

### OFDMA Subcarrier Spacing

Δf = 1 / Tu

Where Tu is the useful OFDM symbol duration.

### SDMA Antenna Array Factor

AF(θ) = Σ wn × exp(j × n × k × d × sin(θ))

### Jain's Fairness Index

J = (Σ Ri)² / (N × Σ Ri²)

Where:
- Ri = Throughput of each user
- N = Number of users
- J = Fairness index

## 9. Expected Outputs

The project generates the following graphical outputs:

1. Link availability and packet delivery graph.
2. Expected retry attempts graph.
3. FDMA and TDMA capacity comparison graph.
4. CDMA processing gain graph.
5. CDMA BER performance graph.
6. OFDMA resource allocation graph.
7. OFDMA throughput graph.
8. SDMA antenna radiation pattern.
9. Multiple access technique comparison graph.
10. OFDMA scheduler throughput graph.
11. User fairness comparison graph.

## 10. Applications

- Cellular communication networks.
- Wireless communication systems.
- GSM and mobile network technologies.
- 4G and 5G communication systems.
- Radio resource management.
- Wireless network scheduling.
- Mobile computing research and simulation.

## 11. Conclusion

This project demonstrates the fundamental concepts of mobile communication and multiple access techniques using Python simulations and graphical analysis.

FDMA separates users by frequency, TDMA by time slots, CDMA by spreading codes, OFDMA by orthogonal subcarriers, and SDMA by spatial separation.

The simulations help understand network capacity, processing gain, throughput, antenna beamforming, and resource allocation. The scheduler analysis also demonstrates the importance of balancing system throughput and user fairness.

## 12. References

- Mobile Computing course materials.
- Mobile Telecommunication Systems.
- GSM and wireless communication concepts.
- Python Documentation: https://docs.python.org/3/
- NumPy Documentation: https://numpy.org/doc/
- Matplotlib Documentation: https://matplotlib.org/stable/
