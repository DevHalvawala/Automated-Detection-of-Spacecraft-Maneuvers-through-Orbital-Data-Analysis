# Automated-Detection-of-Spacecraft-Maneuvers-through-Orbital-Data-Analysis
The main objective of this task is to develop a method that automatically detects spacecraft maneuvers (such as engine burns or orientation adjustments) using orbital data. Specifically, the method should rely on the Semi-Major Axis (SMA) variation over time to identify potential maneuvers, without using explicit maneuver data.

## Key points:

Data-driven Detection: Use the SMA changes over time to infer when maneuvers might have occurred.

Choice of Approach: You can choose either a heuristic (rule-based) approach or a machine learning (ML) approach to detect these maneuvers.


Implementation: Develop Python code that includes:

1.Data preprocessing

2.Feature extraction (e.g., identifying significant changes in SMA)

3.Maneuver detection logic

4.Visualization of the results (showing detected maneuvers over time)


Validation: Compare the detected maneuvers against a set of known maneuver dates provided in a reference table for accuracy.

The goal is to create an effective and efficient method for detecting these orbital maneuvers based solely on SMA variations.
