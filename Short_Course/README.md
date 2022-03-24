# scikit-rf Short Course Outline

## 1. Requirements and Preparation
### 1.1. Python environment setup (Anaconda)
### 1.2. Installation of scikit-rf

## 2. scikit-rf basics
### 2.1. Network: the base class
- Scattering parameters basics
- Creating Network from Touchstone file
- Basic Network properties : .s, .z0, other network parameters (z, y, t, a), discussion shape of arrays (s, etc)
- Slicing, selecting frequency bands. 
- Frequency object discussion. 
- Creating Network from s or other network parameters

### 2.2. Plotting
- Short overview of plotting capabilities

### 2.3. Arithmetic Operations
- +,-,*,/ : Examples with short and delay
- Comparisons

### 2.4. Cascading and de-embedding
- Cascading and inverting: Examples with short and line (cf dedicated tutorial). Mention for 2N-ports
- Simple De-embedding

### 2.5. Interpolation, resampling, stitching
- Resample
- Interpolating
- stitch

### 2.6. Time Domain
- Some theory
- Examples of applications

## 3. Connecting Networks
- connect()
- Circuit

## 4. NetworkSet
- Creating, reading from files
- Uncertainty
- Named-parameters
- Interpolating

## 5. Calibration and De-embedding
### 5.1. Calibration
- Introduction on calibration methods
- One port
- Two port
- Example : one port tiered calibration?

### 5.2. De-embedding
- Introduction (cf doc Jason Ellison)
- Open-short
- Through-only

## 6. VectorFitting
- Introduction
- Examples

## 7. Examples
- Impedance Matching
- Transmission Line Losses