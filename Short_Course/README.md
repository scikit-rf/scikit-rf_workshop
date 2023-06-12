# scikit-rf Short Course Outline

## 0. [Introduction to scikit-rf](0-Introduction_to_scikit-rf.ipynb)

## 1. [scikit-rf basics](1-Networks.ipynb)
### Network: the base class
- Scattering parameters basics
- Creating Network from Touchstone file
- Basic Network properties : .s, .z0, other network parameters (z, y, t, a), discussion shape of arrays (s, etc)
- Slicing, selecting frequency bands. 
- Frequency object discussion. 
- Creating Network from s or other network parameters

### Plotting
- Short overview of plotting capabilities

### Arithmetic Operations
- +,-,*,/ : Examples with short and delay
- Comparisons

### Cascading and de-embedding
- Cascading and inverting: Examples with short and line (cf dedicated tutorial). Mention for 2N-ports
- Simple De-embedding

### Interpolation, resampling, stitching
- Resample
- Interpolating
- stitch

## 2. [Time Domain](2-Time_Domain.ipynb)
- Some theory
- Examples of applications

## 3. [Connecting Networks](3-Connecting_Networks.ipynb)
- connect()
- Circuit

## 4. [NetworkSet](4-NetworkSet.ipynb)
- Creating, reading from files
- Uncertainty
- Named-parameters
- Interpolating

## 5. [Calibration](5-Calibration.ipynb)
- Introduction on calibration methods
- One port
- Two port
- Example

## 6. [Media](6-Media.ipynb)
- Coaxial Example
- Example: Single Stub Optimization
- Rectangular Waveguide
- Example: Rectangular Waveguide Measurement Simulation
- Freespace

## Examples
- [Impedance Matching](Example_Impedance-Matching.ipynb)
- [Transmission Line: Losses on a Loaded Lossy Line](Example_Transmission_Line_Losses.ipynb)
- [Transmission Line: How does the SWR vary along a line?](Example_SWR_along_a_line.ipynb)
- [Interpolating between Networks with NetworkSet](Example_Interpolating_NetworkSet.ipynb)
- [Tapered Transmission Lines](Example_tapered_transmission_lines.ipynb)
