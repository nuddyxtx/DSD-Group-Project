# DSD Group Project: Drive-Through Facility Controller

The entire circuit is implemented and can be simulated using Logism Evolution

## Circuit Design

### `main` Circuit
This is the top-level circuit that integrates all components. It contains:
- State register, which holds the current state of the FSM.
- Master clock and reset pins.
- Input pins for Enter and Exit sensors
- Output components: LEDs for the entrance and exit traffic lights and a 7 Segment Display for the car count.



### Sub-Circuits

1.  **`State_Transition`:** This sub-circuit contains the combinational logic that calculates the next state of the FSM.

2.  **`State_to_Lights`:** This is the output logic circuit for the traffic lights. 

3.  **`State_to_Count`:** This circuit decodes the current state to determine the number of cars in the passage.


## Project Files

-   **`Traffic_Light_Project.circ`**: The complete Logisim-evolution project file containing all circuits and logic.
-   **`Project_tables.xlsx`**: A spreadsheet containing the state transition table, output tables, and Karnaugh maps used to derive the boolean expressions for the combinational logic.


## Group Members
- Adriana Gomez
- Andrew Brugner
- Blaine Pavlock
- Elisa Garcia
- Kelli Garcia
- William Henderson
