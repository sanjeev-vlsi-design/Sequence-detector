Sequence Detector
A Sequence Detector is a digital circuit designed to detect a specific pattern of bits in a serial input stream. This project demonstrates the design and implementation of a sequence detector using Verilog, showcasing its application in communication systems, error detection, and control logic.

Features
Pattern Recognition: Detects a predefined sequence of bits in a serial input.
Configurable Patterns: Easy to modify for different bit sequences.
Overlapping Sequences: Supports detection of overlapping patterns in the input stream.
Synchronous Design: Operates in sync with the clock signal for reliable detection.
Project Highlights
Inputs:

Serial Input: The stream of bits to be monitored.
Clock: Synchronizes the sequence detection process.
Reset: Resets the detector to its initial state.
Output:

Detection Signal: Indicates when the desired sequence is detected in the input stream.
Operation Modes:

Non-Overlapping Mode: Detects the sequence without considering overlapping patterns.
Overlapping Mode: Detects the sequence even when it overlaps with previously detected patterns.
Workflow
Initialization: The detector starts in the initial state upon reset.
Pattern Matching:
Monitors the serial input bit-by-bit.
Transitions through states based on the incoming bits and the desired pattern.
Sequence Detection: Activates the detection signal when the entire pattern is matched.
