---

# Total Magnetic Field Calculation in Feed-forward Network

This Python script calculates the total magnetic field strength (in femtotesla) generated by a feed-forward neural network. The program takes into account the material choice (space or neural tissue) and corresponding parameters, as well as user-defined values for w (neuron weight) and u (subthreshold synaptic input).

## Prerequisites

Before using this code, you need to have the following:

- Python installed on your system.
- A Python environment with the `math` module available.

## Running the Code

1. **Opening the Code**:

   - Copy the code into a Python environment or a Python file (e.g., `total_magnetic_field.py`).
   - Execute the script using your preferred Python environment.

2. **Input Values**:

   - The program will prompt you to choose a material (space or neural tissue) and enter the distance from the neurons (in nanometers). You will also be prompted to provide w and u values for each neuron.

   ```python
   Choose a material:
   1. Space
   2. Neural tissue
   Enter your choice (1 or 2): [enter_choice]
   Enter the distance from the neurons (in nanometers): [enter_distance]
   (w must be between 0 and 1)
   Enter the value of w for neuron [neuron_number]: [enter_w_value]
   Enter the value of u (in picoamperes) for neuron [neuron_number]: [enter_u_value]
   ```

3. **Viewing the Results**:

   - The script will calculate the magnetic field strength (MF) for each neuron and display the individual currents. It will also provide the total magnetic field strength for the entire feed-forward network.

   ```python
   Calculated currents (in femtotesla) for each neuron:
   Neuron 1: [current_value] femtotesla
   Neuron 2: [current_value] femtotesla
   ...
   Total MF: [total_field] femtotesla
   ```

## Usage Tips

- Ensure you provide accurate values for w, u, and the distance from the neurons based on your data or measurements.
- The calculation assumes specific values of μ (mu) for the chosen material. Review and adjust these values if necessary.

## Support and Contact

For any questions or issues, feel free to contact the author at k11shahryari@gamil.com

---
