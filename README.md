# 3-Bit-Custom-Counter-Design-with-Control-Input

Quartus Schematics

Top Level:

<img width="619" alt="Screenshot 2025-07-09 at 10 33 05 PM" src="https://github.com/user-attachments/assets/ff6a32af-7227-4d60-bec8-fabea9e68817" />

FF input signals:

<img width="629" alt="Screenshot 2025-07-09 at 10 33 19 PM" src="https://github.com/user-attachments/assets/d6e31fe6-c352-48bd-b26c-510e0425ccc6" />

Model Sim:

<img width="626" alt="Screenshot 2025-07-09 at 10 33 35 PM" src="https://github.com/user-attachments/assets/d5dd37f8-4e93-490f-a86b-28c7c9bf948c" />

Questions:

Another design for the counter circuit might use a Moore machine where the state bits are not used as the outputs. For example, the state bits might be the binary count sequence 0 – 6. How would this design compare with Design I (assuming your assigned count sequence was not the straight binary count sequence 1 to 6)? Which design is likely to require the fewest gates? Justify your answer

The alternative design would use fewer gates than Design I because it simplifies the counter logic with a standard binary sequence. Design I’s custom non-binary mapping requires more complex combinational logic, increasing the gate count because of irregular transitions.




I designed and implemented a 3-bit counter simulating a six-sided die roll using a Moore machine with state bits as outputs. The circuit was built with D flip-flops and logic gates and was verified through simulation and by our TA. I learned key concepts in sequential logic design, state machines, and debugging techniques.
