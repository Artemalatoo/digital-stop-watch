
Project Title: Clock-Based Digital Stopwatch in Logisim
Student Name: Artem
Faculty: IT, Ala-Too International University
Department: Artificial Intelligence and Robotics
Date: April 15, 2025

1. Objective
The goal of this project is to design and simulate a digital stopwatch using the Logisim simulator that counts time in MM:SS format. It includes control functions like start, stop, and reset.

2. Tools Used
- Software: Logisim Evolution
- Logic Components:
  - Counters
  - Clock
  - 7-segment displays
  - Logic gates
  - Multiplexers
  - Control inputs

3. Design Overview
Modules:
- Clock Divider: Converts Logisim's base clock into a 1Hz signal for 1-second steps.
- Seconds and Minutes Counter: BCD counters increment seconds and propagate carry to minute counters.
- 7-Segment Encoder: Converts binary to digit representation.
- Control Logic: Handles start, stop, and reset with input buttons.

4. Results
The stopwatch was successfully implemented and tested with:
- Accurate time counting
- Proper rollover from 59 to 00 seconds and minutes
- Functional control using input buttons

5. Screenshots
*(Add screenshots of your Logisim circuit during simulation)*

6. Conclusion
This stopwatch project helped understand:
- Digital clock logic
- Binary counters and BCD
- Real-time simulation in Logisim
- Control signal design and circuit timing
